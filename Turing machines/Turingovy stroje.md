[Zdroj](https://www.fit.vutbr.cz/study/courses/TIN/public/Prednasky/tin-pr05-ts.pdf)
- Churchova (Church-Turingova) teze: Turingovy stroje (a jim ekvivalentní systémy)
definují svou výpočetní silou to, co intuitivně považujeme za efektivně vyčíslitelné.
- Je šestice tvaru $M = (Q,\Sigma, \tau, \delta, q_{0},q_{F})$, kde
	- $Q$ je konečná množina stavů
	- $\Sigma$ je konečná množina symbolů vstupní abycedy
		- $\Delta \notin \Sigma$
	- $\tau$ je konečná množina symbolů páskové abecedy
		- $\Sigma \subset \tau$, $\Delta \in \tau$
	- $\delta$ je přechodová funcke
		- $\delta : (Q \; \backslash \; \{q_{F}\}) \times \tau \rightarrow Q \times (\tau \cup \{L,R\})$, kde $L,R \notin \tau$
	- $q_{0}$ je počáteční stav
	- $q_{F}$ je koncový stav
- Třída jazyků přijímaných TS (rekurzivně vyčíslitelných) je shodná se třídou jazyků typu 0