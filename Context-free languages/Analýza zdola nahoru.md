 - Jde o převod *BKG* na *ZA*
- Bude se jednat o rozšířený *ZA*, který bude přijímat přechodem do koncového stavu
	- $M = (\{q,r\}, T, N\cup T \cup \{\#\}, \delta,q,\#,\{r\})$
	- je vhodné mít vrchol zásobníku vpravo
- Tři druhy přechodů
	1. Redukční přechody
		- $(\beta, \alpha) \in P \Rightarrow (q, \beta) \in \delta(q, \varepsilon, \alpha)$
		- obsluhuje neterminály
	2. Posunovací přechody
		- $\forall a \in \Sigma : \delta(q,a, \varepsilon) = \{(q,a)\}$
		- obsluhuje terminály
	3. Ukončující přechody
		- $\delta(q, \varepsilon, \#S) = \{(r,\varepsilon)\}$ 
- Vstupní řetězec se snažíme redukovat na počáteční neterminál
