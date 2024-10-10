- Před převodem do CNF je třeba provést **popořadě** následující transformace 
	1. Odstranění nic negenerujících terminálů
	2. Odstranění nedostupných terminálů
	3. Odstranění $\varepsilon$-pravidel
	4. Odstranění jednoduchých pravidel
- Po provedení všech 4 kroků dostáváme **vlastní** gramatiku, kterou můžeme převést
- Následně převádíme pravidla do tvaru vyhovujícímu CNF:
	- $S \rightarrow aAB \Rightarrow S \rightarrow <a><AB>$, kde $< \alpha >$ je jeden symbol
	- $<a> \; \rightarrow a$
	- $<AB> \; \rightarrow AB$