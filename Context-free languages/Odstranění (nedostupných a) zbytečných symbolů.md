- Výstup: Gramatika $G$ bez zbytečných symbolů
- Metoda:
	1. Vypočteme na $G$ množinu $N_{t}$
	2. Vytvoř $\overline{G} = (N_{t} \cup \{S\}, \Sigma, \overline{P},S)$, kde
		- $\overline{P} = \{A \rightarrow \alpha \mid (A \rightarrow \alpha) \in P \land A \in N_{t} \land \alpha \ in (N_{t} \cup \Sigma)^{*}\}$
	3. Vytvoř  množinu $V$ nad $\overline{G}$
	4. Výslednou gramatiku vytvoř jako:
		- $N^{'} = N_{t} \cap V$
		- $\Sigma^{'} = \Sigma \cap V$
		- $P^{'} = \{A \rightarrow \alpha \mid (A \rightarrow \alpha) \in P \land A \in N^{'} \land \alpha \in V^{*}\}$