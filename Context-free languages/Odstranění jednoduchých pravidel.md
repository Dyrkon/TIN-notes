- Výstup: Gramatika bez jednoduchých pravidel
- Před odstraněním jednoduchých pravidel je třeba odstranit $\varepsilon$-pravidla
- Algoritmus:
	1. Pro všechny $A \in N$ vypočítáme množinu $N_{A}$, kde budou neterminály na pravé straně jednoduchých pravidel (zde $B$)
		- $N_{A} = \{B \in N \mid A \Rightarrow^{*} B\}$
	2.  Pokud se $B$ derivuje na terminál, tak do $P^{'}$ přidej nová pravidla $A \rightarrow \alpha$ pro všechny $A_{i}$, kde $B \in N_{A_{i}}$
	3. Výsledná množina pravidel $P^{'}$ neobsahuje jednoduchá pravidla