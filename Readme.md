# Architecture Machine – TP DigLog

##  Description
Ce dépôt contient les travaux pratiques réalisés dans le cadre du module **Architecture Machine** durant le **1er semestre**.  
Les circuits ont été conçus et simulés à l’aide du logiciel **DigLog**.

Ces TP visent à comprendre le fonctionnement interne des composants de base d’un ordinateur à travers la conception de circuits logiques.

##  Outils requis
-  **DigLog** (obligatoire)
- Les fichiers des circuits sont au format **`.lfg`**

 Sans le logiciel **DigLog**, il n’est pas possible d’ouvrir ou de simuler les circuits.

##Circuits réalisés
- **Additionneur / Soustracteur**
- ** UAL (Unité Arithmétique et Logique)**
- ** Registres **
- ** Banc de registres **
- ** Pile (Stack)**
- ** File (Queue)**
- ** Banc de registres **
- ** multiplieur séquentiel **


##  Dépendance entre les circuits
 **Les circuits dépendent les uns des autres.**  
Pour un bon fonctionnement :

- Tous les fichiers **doivent être ouverts en même temps** dans DigLog
- Certains circuits utilisent d’autres circuits comme **sous-modules**
- En particulier, le circuit **Additionneur / Soustracteur** est une **base essentielle** utilisée par d’autres circuits (notamment l’UAL)

 Si un fichier manque ou n’est pas ouvert, le circuit peut ne pas fonctionner correctement.
