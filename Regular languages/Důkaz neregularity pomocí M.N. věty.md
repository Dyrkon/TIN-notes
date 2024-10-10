- Intuice proč můžeme dokázat neregularitu:
	- Vezmeme [[Myhill-Nerodova věta|větu 3]] a neregulární jazyk $L = \{a^nb^n \mid n \geq 0\}$
	- Minimální automat pro takovýto jazyk by byl nekonečný [zdroj](https://youtu.be/uQF-vwjvVyY?list=PLdn7h8pmNOL-dewLJKrUIlDNtPBRytnRB&t=3280)
	- [[Pravá kongurence a prefixová ekvivalence|Relace prefixové ekvivalence]] $\sim_L$ by pak nebyla konečná
- Intuice pro výběr slova
	- Chceme aby nám pro jeden výběr padlo slovo po konkatenaci padlo do jazyka a pro druhý výběr z jazyka vypadlo
- Samotný důkaz pak provádíme následovně:
	- Pro ukázku použijeme jazyk $L = \{a^nb^n | n\geq 0\}$
	1. Předpokládáme, že $L \in \mathcal{L}_3$
	2. Z [[Myhill-Nerodova věta|2. M.N.]] věty plyne, že $\exists n \in \mathbb{N}: |\Sigma^*/\sim_L| = n$
	3. Vybereme $n+1$ slov z množiny $\Sigma^*$:
		- $\varepsilon, a, a^2, a^3,...,a^n$
	4. Zavedeme parametry $i,j \in \mathbb{N}$:
		- $0 \leq i \leq n \land 0 \leq j \leq n \land i \neq j$
	5. ![[Pravá kongurence a prefixová ekvivalence#^846b4a]]
	6. $a^i \sim_L a^j \Leftrightarrow \forall w \in \Sigma^* : a^iw \in L \Leftrightarrow a^jw \in L$
	7. Vybereme slovo $w = b^{i}$ (protipříklad)
		- $a^i = a^ib^i \in L$
		- $a^j = a^jb^i \notin L$
		- Tedy: $a^i \not\sim_{L} a^j$
	8. Z toho plyne, že žádné dvě různé slova $a^i, a^j$ z našeho výběru nejsou v relaci $\sim_{L}$ tedy každé z nich spadá do jiné třídy rozkladu $\Sigma^*/\sim_{L}$
	9. Těchto tříd rozkladu $\Sigma^*/\sim_{L}$ je tedy alespoň $n+1$
	10. To je ve sporu s původním předpokladem, že $|\Sigma^*/\sim_{L}| = n$
	11. Jazyk $L \not\in \mathcal{L}_{3}$