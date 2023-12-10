---
title: "Formulaire de réponse pour le test 2"
output: html_document
---

**Prénom Nom Groupe**


***
### Question 1

* Calculer la probabilité de battre un record à l'épreuve $m$

#### Réponse :

Notons $R_m$ L'évènement "Un record a été battu à lépreuve m".  
Puisque les lois de probabilité des variables $X_n$ sont uniformes, faisont un dessin:  
- cas $R_1$  
![image](2D_U1gtU0.png =400x)  
On peut observer que la probabilité que $X_1$ soit un record est l'air du triangle, soit $\frac {1 * 1} {2}$

- Cas $R_2$  
Ici Il faut à la fois que $X_2$ soit supérieure à $X_0$ (à gauche) et $X_1$ (à droite) :  
![U2gtU0](U2gtU0.png =300x)
![U2gtU1](U2gtU1.png =300x)  
Au final, en faisant l'intersection, on obtient une piramide inversée à base carré :  
![U2gtU0andU1](U2gtU0andU1.png =400x)  
Qui a pour volume $\frac {1*1} {3}$

- Généralisation au $X_n$ avec $n \ge 3$ :  
On peut assez facilement comprendre que le shémas se répète. Ainsi, la probabilité que $X_n$ soit un reccord est l'espace occupé par la piramide de base 1 et de hauteur 1 en dimmention $n+1$.  
On rappel que la formule de l'espace occupé par une pyramide de dimmension $n$ est $\frac {A*h} {n}$

Au final $P(R_m) = \frac {1 * 1} {m+1} = \frac {1} {m+1}$.  


***
### Question 2

* Donner l'espérance de $N$ pour $n = 27$.

#### Réponse :


***
### Question 3

* Calculer ${\rm E}[Y_n]$.

#### Réponse :


***
### Question 4

* Calculer la valeur de la variance Var$[Y_3]$.

#### Réponse :


***
### Question 5

* Calculer Var$[Y_n]$ pour tout $n \geq 2$.

#### Réponse :


***
### Question 6

* Combien de tirages suffisent pour qu'avec une probabilité supérieure à 0.99, $A_{n-1}$ soit proche de la valeur 1/2 à $10^{-2}$ près.

#### Réponse :


***
### Question 7

* Déterminer la valeur de $c$.

#### Réponse :


***
### Question 8

* Déterminer la fonction de répartition de la variable $Y$. Donner sa valeur au point $t = 2/3$.

#### Réponse :


***
### Question 9

* Ecrire un algorithme de simulation d'un couple de densité $f(x,y)$.

#### Réponse :


***
### Question 10

* On pose $Z =  X Y$. Déterminer la densité de la loi de la variable $Z$.

#### Réponse :

