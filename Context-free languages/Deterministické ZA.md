- Mají striktně menší vyjadřovací sílu než NZA
	- jazyk $L = \{ww^{R} \mid w \in \Sigma^{+}$ nelze přijímat žádným DZA
		- DZA neví kdy končí $w$ a začíná  $w^{R}$
- To, zda je *BKJ* jazykem nějakého DZA není obecně rozhodnutelné
- Aby byl ZA deterministický, tak musí platit alespoň 1 z podmínek pro $\forall q \in Q : \forall z \in \tau$: ([vysvětlení](https://youtu.be/Vp_oBaNiIFg?list=PLdn7h8pmNOL-dewLJKrUIlDNtPBRytnRB&t=2770))
	1. $(\forall a \in \Sigma : \mid \delta(q,a,z)\mid \; \leq 1) \; \land \mid\delta(q,\varepsilon,z)\mid \; = 0$
	2. $(\forall a \in \Sigma : \mid \delta(q,a,z)\mid \; = 0) \; \land \mid\delta(q,\varepsilon,z)\mid \; \leq 1$