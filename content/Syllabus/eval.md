+++
title = "Evaluation"
date = 2020-09-04T17:28:49+02:00
weight = 15 
chapter = false
+++

-------

## Les tests

La note finale est composée de 3 tests:

1) **Une note sur les séries d'exercices**. Pour que **cette note compte**, il faut **au moins avoir rendu 8 séries**, i.e. avoir posté ses réponses sur les [quiz](https://moodle.unige.ch/course/view.php?id=8193) 8 fois.  La première série ne contribue pas à la note finale, mais sert à vous familiariser avec la manière de vous évaluer. 

2) **Un contrôle continu** lors du cours du 27.10.2020. Il s'agira d'un qcm. 


3) **L'examen de fin de semestre**. Il s'agira aussi d'un qcm.

Pour chaque test (quiz, contrôle continu et exa finale), le barème appliqué est le barème fédéral soit: note = 5 * (pts obt/pts tot) + 1. Les notes sont arrondies à la demi avec la convention les conventions usuelles (3,75 devient 4,0 et 5,67 devient 5,5).


## Calcul de la note finale

Le poids de chaque test  est le suivant: 15% série d'exo , 25% contrôle continu et 60% examen final.

**La note finale est la note maximale entre la note de l'examen final et la moyenne pondérée de tous les tests (série, c.c., exa final).** 

Elle est arrondie à la demi selon la même convention que pour les tests.

## Planning 

Le planning ci-dessous vous indique, entre autres, les deadlines pour poster vos quiz sur [Moodle](https://moodle.unige.ch/course/view.php?id=8193). Cela doit être fait pour **chaque mardi avant minuit**. Il n'y aura **pas de possibilité de le faire après le délai**.

{{<mermaid>}}
gantt
        dateFormat  YYYY-MM-DD
        title Planning séries & contrôle continu
        section Séries 
        Série 1            :    des1, 2020-09-15, 7d
        Série 2            :    des2, after des1, 7d
        Série 3            :    des3, after des2, 7d
        Série 4            :    des4, after des3, 7d
        Série 5            :    des5, after des4, 7d
        Pas de série       :done,    des6, after des5, 7d
        Série 6            :    des7, after des6, 7d
        Sem. de lec. :done,  des8, after des7, 7d
        Série 7            :    des9, after des8, 7d
        Série 8            :    des10, after des9, 7d
        Série 9            :    des11, after des10, 7d
        Série 10           :    des12, after des11, 7d
        Série 11           :    des13, after des12, 7d
        section Deadline séries
        Quiz 1 (22 sept)            :crit, active, after des1, 1d
        Quiz 2 (29 sept)            :crit, active, after des2, 1d
        Quiz 3 (06 oct)             :crit, active, after des3, 1d
        Quiz 4 (13 oct)             :crit, active, after des4, 1d
        Quiz 5 (27 oct)             :crit, active, after des5, 1d
        Quiz 6 (10 nov)             :crit, active, after des8, 1d
        Quiz 7 (17 nov)             :crit, active, after des9, 1d
        Quiz 8 (24 nov)             :crit, active, after des10, 1d
        Quiz 9 (01 déc)             :crit, active, after des11, 1d
        Quiz 10 (08 déc)             :crit, active, after des12, 1d
        Quiz 11 (15 déc)             :crit, active, after des13, 1d
        section Contrôle continu 
        Contrôle continu (27 oct)          :crit, after des6, 1d
        Examen final (?? jan) :scream:              :crit, 2020-12-31, 1h
{{< /mermaid >}}


<!--
to insert a gif, must save the gif into a folder in which the gif will appear.

![Dance](/Syllabus/dance.gif?classes=shadow)

![Minion](https://octodex.github.com/images/minion.png)

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif?width=500px)
-->

