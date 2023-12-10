1- Des de dins de la carpeta del projecte prjava02 del teu ordinador:
	a) Crea una branca de nom branca00. Trobaràs informació de com fer-ho al primer enllaç de la documentació, dins de la secció "Creating a new branch".
		git branch branca00
	b) Accedeix a la branca00. Trobaràs informació de com fer-ho al primer enllaç de la documentació, dins de la secció "Switching Branches".
		git checkout branca00
	c) Comprova des de l'interpret d'ordres l'estat del projecte i a quina branca et trobes.
		git status -b
	
5- Torna a la branca main del projecte. Comprova l'estat del projecte. Mostra l'historial de la branca main. Quina diferència hi ha amb l'historial de la branca branca00?
	git checkout main
	git status
	git log
	git log main..branca00

6- Des de geany, actualitza el contingut del fitxer Prjava02.java. Pots veure l'última línia afegida?. Per què?
	No. Aquest canvi ha estat fet sota la branca00, no pas sota la branca main.
	
7- Torna a la branca branca00. Des de geany, actualitza el contingut del fitxer Prjava02.java. Pots veure
l'última línia afegida?. Per què?.
	git checkout branca00
	geany Prjava02.java
	Només veiem els canvis fets a la branca actual. Els canvis fets a la branca main no són visibles fins que tornem a fer un checkout a aquesta branca.
	
10b- Fusiona (merge) la branca branca00 amb la branca master. Trobaràs informació a la documentació.
	git merge branca00
	
12- Continuant dins de la branca main:
	a) Fes un push del dipòsit local al dipòsit remot.
		git push
	b) Des de Github, actualitza la pàgina web del projecte, i comprova que els canvis han estat realitzats correctament.
	c) Comprova que només s'ha actualitzat la branca main únicament. Per què?.
		El push només afecta a la branca actual.
		
14- Fes:
	a) Un push de branca01 del dipòsit local al dipòsit remot.
		git push branca01
	b) Des de Github, actualiza la pàgina web del projecte, i comprova que s'ha generat la branca01 a Github i que a Prjava02.java estan els darrer canvis realitzats.
	c) A quants commits de distància (commit ahead) està de la branca main?
		A 1 commit ahead.
