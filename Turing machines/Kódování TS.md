- Kódujeme TS - příklad
	- Stavy, tak aby byli odlišitelné
		- včetně $q_{0}$ a $q_{1}$
		-  Postup:
			- uspořádáme množinu stavů $Q$ do posloupnosti
			- stav $q_{j}$ zakodujeme jako $0^{j}$
	- Symboly z $\tau$
		- Postup:
			- předpokládáme, že $\tau = \Sigma \cup \{\Delta\}$
			- uspořádáme $\Sigma$ do posloupnosti $a_{1}, a_{2},...,a_{n}$
			- zvolíme tyto kody
				- $\Delta \rightarrow \varepsilon$
				- $L \rightarrow 0$
				- $R \rightarrow 00$
				- $a_{i} \rightarrow 0^{i+2}$
	- Přechodové funkce $\delta$
		- $\delta(p,x) = (q,y)$, kde $y = \tau \cup \{L,R\}$ reprezentujeme čtveřicí $(p,x,q,y)$
		- Postup:
			- kodujeme zřetězením kodů $p,x,q,y$
			- použijeme $1$ jako oddělovač