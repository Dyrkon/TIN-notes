- Nazývá se *BKG* jestliže všechna pravidla z $P$ mají tvar:
	- $A \rightarrow \alpha, A \in N, \alpha \in (N \cup \Sigma)^{*}$
- Schopnost sebevkládání
- Definovaná pomocí čtveřice
	- $G = (N,\Sigma,P,S)$
		- N => konečná neprázdná množina neterminálů
		- $\Sigma$ => konečná neprázdná množina terminálů
			- Platí, že $N \cap \Sigma = \emptyset$
		- P => konečná množina pravidel
		- S => počáteční symbol
- Jazyk, který gramatika generuje zapíše me jako výsledek posloupnosti derivací:
	- $L(G) = \{w \in \Sigma^{*} \mid S \Rightarrow^{+} w\}$