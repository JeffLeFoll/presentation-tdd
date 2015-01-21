TDD - Test Driven Development

Pour commencer un test unitaire c'est quoi?
	[Tour de table] Quand on vous dit "test unitaires" vous pensez à quoi ? (pas de question piege)

Définition d'un bon test unitaire (James Shore)
	S'execute rapidement
		[Note] tests lents => personnes ne les execute, une fois sur l'IC le build est en echec et a tendence à le rester si le problème n'est pas réglé rapidement
	Fournis une ceinture de sécurité pour le refactoring
		[Note] Des tests en nombre et bien fait, permette à l'equipe d'avoir la confiance et le courage de refactorer le code, amélierorer le design, de réduire la dette technique
	Documente le but du code (c'est une spec)
		[Note] La doc, les wiki, les longs bloc de commentaires, tout ça finit par ne plus etre a jour, par se predre, au final seul reste le code, plus ou moins propre, avec plus ou moins de tests documentant les fonctionnalitées et les RGs
 	Alerte l'équipe des régression
 		[Note] Les tests ont besoin d'etres sufisament complet pour permettre d'alerter l'équipe sur l'apparation de regression. Les tests manuel sont lent et couteux, des tests complets et bien écris nous permet d'avoir confiance dans les modifications que l'on fait.

 Un bon test suit la régle F.I.R.ST :
 	Fast  -> 
 	Independant  -> 
 	Repeatable  -> 
 	Self-validating  -> 
 	Timely -> 