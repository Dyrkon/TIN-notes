- Vytváříme množinu $N_{t}$
	- Tu tvoří neterminály, které generují terminály
	- Jelikož $\varepsilon \in T$, tak $N_{\varepsilon} \subseteq N_{t}$
- Metoda pro výpočet množiny:
	1. $N_{0} = \emptyset, i = 1$
	2. $N_{i} =$ neterminál, který je v pravidlech, a derivuje se na
		- Něco z $N_{i-1}$
		- Terminál
	1. Pokud jsme v daném kroku $i$ nic do $N_{i}$ nepřidali, končíme, jinak jdeme na (2)