# Fauteuil Electrique

## Le projet 

Date début : Eté 2013

Suite à la récupération de 2 fauteuils roulants électriques, l'objectif premier est de prendre le contrôle de la base roulante en vue de pouvoir l'enrichir d'une intelligence embarquée. 

Le point fort de la base roulante de ce type : 
* autonomie longue (2x batterie plomb 12V@80Ah )
* roule en extérieur
* levée des contraintes liées à la taille du robot

Au début de ce projet, les interrogations sont multiples : 
* type de moteurs : CC simples ? autres ? 
* caractéristiques électriques ? 
* éléments récupérables ? 

## Synthèse étapes : 
[Le 04 /09/2013 : Séance 1 : Xav+Pat : démontage fauteuil HS - accès moteur - tests de base] (https://github.com/crepp/fauteuil_elec/blob/master/historique.md#s%C3%A9ance-1---8h10h---le-4092013---xav--pat)



# Câblage électrique du robot

![mon beau svg](https://rawgithub.com/crepp/fauteuil_elec/master/cablage_elec.svg)



![mon beau svg](https://rawgithub.com/crepp/fauteuil_elec/master/test.svg)


### Intensité max en fonction du diamètre de câble 

section => Imax pour une longueur < 1m   (= 2m AR)  
1,5 mm2 => 6A  
2,5 mm2 => 10A  
4 mm2   => 16A  
6 mm2   => 30A  

C'est approx section x 4 ou 5.  


## Interfaces utilisées

La contrainte : interfaces pour moto-réducteurs CC 15A nominal en 12V voire 24V

* [Syren 25A - 69€] (http://www.gotronic.fr/art-commande-de-moteur-25a-syren25-11571.htm)
* [SaberTooth 25A x2 - 109 €] (http://www.gotronic.fr/art-commande-sabertooth-2x25a-11575.htm)
