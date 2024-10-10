- Binární relace $\vdash_{P}$ definovaná na množině konfigurací:
$$
\begin{gather}
(q,w, \beta) \vdash_{P} (q^{'}, w^{'}, \beta^{'}) \overset{def}{\Longleftrightarrow} w = aw^{'} \land  \\ \beta = Z\alpha \land \beta^{'} = \gamma\alpha \land (q^{'}, \gamma) \in \delta(q,a,Z)
\end{gather}
$$
- Je-li $a = \varepsilon$, pak přechod nazýváme $\varepsilon$-přechod
- Jazyk přijímaný zásobníkovým automatem A definujeme:
	- $L(P) = \{w \mid (q_{0},w,Z_{0}) \vdash_{P}^{*} (q,\varepsilon, \gamma)\land q \in F\}$
- Do grafu kreslíme přechody následovně:
	- $a,o/p$, kde $a \in \Sigma \cup \{\varepsilon\}, o \in \tau, p \in \tau^{*} \cup \{\varepsilon\}$
		- neboli: přečteme $a$, ze zásobníku odebereme $o$ a na zásobník dáme $p$
- Přechody můžeme psát i parametricky ([ukázka](https://youtu.be/Vp_oBaNiIFg?list=PLdn7h8pmNOL-dewLJKrUIlDNtPBRytnRB&t=2274)), kdy si specifikujeme množinu symbolů
	- které čteme $\alpha$
	- které dáváme na zásobník $\beta$
	- Přechod pak můžeme psát například takto
		- $\alpha,\beta/\alpha\beta$