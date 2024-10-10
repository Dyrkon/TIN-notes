1. Vytvoříme $\varepsilon$-uzávěr
2. Vytváříme nové přechody mezi $\varepsilon$-uzávěry:
	- $\varepsilon$-uzávěr$(0)$ = $\{0,1,3\} = A$
	- $\delta(A,a) =$ $\varepsilon$-uzávěr$(\{1,2\}) = \{1,2,3\} = B$
		- Kam se z $0,1,3$ dostanu pomocí $a$:
			- např. do $1,2,3$
	- Můžeme využívat existující $\varepsilon$-uzávěry a spojovat je
3. Jako stavy zakreslíme písmena $A,B,..$ a podle přechodů, který jsme k nim vyráběli nakreslíme hrany
- Tento algoritmus převede RKA na DKA, to ale nevadí, protože každý DKA může být zároveň NKA (ale nikdy naopak)