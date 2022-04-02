## Historique 

## Séance 1 - 8H/10H - le 4/09/2013 - Xav + Pat
Démontage du fauteuil HS jusqu'à accès aux moteurs  
Repérage des éléments fonctionnels  
Premier visuel des moteurs :  
* moteurs réducteurs CC à balai avec "vis" pour les charbons
* caractéristiques 0,180 Kw soit 180W soit en 12V = 15A !!

Premier essai de mise en action : 
* Echec sur alim labo 12V/ 10A ! (chute tension... de l'alim !)
* Echec sur alim PC 12V / 10A ! (léger mouvement... ) 

Deuxième essai de mise en action du moteur de direction avant : 
* OK sur alim 12V/10A : moteur CC également mais de moindre puissance 

Conclusion de cette première séance : 
* nécessité batteries chargées pour alimenter les moteurs au vu de la puissance nécessaire 
* nécessité d'une interface de commande 15A par moteur minimum... 

> si on considère une conso de 15A nominal, il faut une batterie de au minimum 15A x 3 = 45 Ah !

## Entre séance 1/2 : 
Recherche interface possible Gotronic pour moteur CC 15A: 
* [Syren 25A - 69€] (http://www.gotronic.fr/art-commande-de-moteur-25a-syren25-11571.htm)
* [SaberTooth 25A x2 - 109 €] (http://www.gotronic.fr/art-commande-sabertooth-2x25a-11575.htm)
* [BasicMicro - 2 x 30 A - 118€] (http://www.gotronic.fr/art-commande-robot-claw-2x30a-17506.htm)

Toutes ces interfaces permettent le contrôle par tension analogique 0-5V (et PWM), impulsion servo (RC), et aussi par série TTL (Uart) (multi possible sur même bus)

Xav a 2 batteries 100Ah chacune chargées qui seront utilisées. 
Se pose aussi la question d'un dispositif ultra-fréquence pour "récupérer" des batteries au plomb HS... (celles sur le robot)

## Séance 2

