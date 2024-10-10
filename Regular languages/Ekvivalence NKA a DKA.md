- To, že je NKA a DKA ekvivalentní můžeme ukázat pomocí determinizace
- Metoda:
	1. polož $Q' = 2^Q$
	2. polož $q_0' = \{q_0\}$
	3. Polož $F' = \{S \mid S \in 2^Q \land S \cap F = \emptyset\}$
	4. Pro všechna $S \in 2^Q$ a pro všechna $a \in \Sigma$ a plož:
		-  $\delta'(S,a) = \underset{q\in S}{\cup}\delta(q,a)$
- Spojíme tedy všechny přechody jdoucí z jednoho stavu s jedním elementem z abecedy do jednoho