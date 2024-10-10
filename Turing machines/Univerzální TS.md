- Zavádí koncept "programovatelného" stroje, který umožňuje na vstupu specifikovat konkrétní TS (tj. program) i data, nad nimiž má tento stroj pracovat
- TS, který má být simulován budeme kodovat
- Univerzální TS můžeme navrhnout například takto
	- TS bude mít 3 pásky
		1. páska, zadání (a poté výstup)
		2. pásku využíváme k simulaci pracovní pásky původního stroje
		3. pásku používám pro záznam řídícího stavu simulovaného stroje a aktuální pozici hlavy