- Vytváříme množinu $V$
- Metoda pro výpočet množiny:
	1. $V_{s} = \emptyset, i = 1$
	2. $V_{i} =$ symboly z předchozího kroku $\cup$ neterminál $X$, který je na pravé straně pravidla, které je ve formě $A \rightarrow \alpha X \beta$, kdy platí, že $A \in V_{i-1}$
	3. Pokud jsme v daném kroku $i$ nic do $N_{i}$ nepřidali, končíme, jinak jdeme na (2)