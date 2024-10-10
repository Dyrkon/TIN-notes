- Gramatika je bez $\varepsilon$-pravidel pokud neobsahuje žádné $\varepsilon$-pravidlo
	- pokud $\varepsilon \in L(G)$, tak gramatika obsahuje jediné $\varepsilon$-pravidlo
		- $S \rightarrow \varepsilon$
		- $S$ se pak nevyskytuje na žádné pravé straně pravidla z gramatiky
- Algoritmus: ([ukázka](https://youtu.be/Vp_oBaNiIFg?list=PLdn7h8pmNOL-dewLJKrUIlDNtPBRytnRB&t=8733))
	1. Vypočítejte množinu $N_{\varepsilon} = \{A \in N \mid A \Rightarrow^{+} \varepsilon\}$ ([ukázka](https://youtu.be/Vp_oBaNiIFg?list=PLdn7h8pmNOL-dewLJKrUIlDNtPBRytnRB&t=7783))
		-  Začínáme s $N_{\varepsilon} = \emptyset$, $\emptyset^{*} = \varepsilon$
		- Pravidla, jejichž pravá strana je složena z $N_{\varepsilon}^{i-1}$ iterace
	2. Každé pravidlo, které obsahuje neterminál/y z $N_{\varepsilon}$ rozepiš na pravidlo, kde jeden neterminál z $N_{\varepsilon}$ nahradíme za $\varepsilon$
		- Počet takto nově vytvořených pravidel je $2^{k}$
	3. Vypusť všechna $\varepsilon$-pravidla
	4. Pokud $S \in N_{\varepsilon}$ pak 
		- přidej nový neterminál $S^{'}$
		- přidej nové pravidlo $S^{'} \rightarrow \varepsilon \mid S$