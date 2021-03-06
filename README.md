# IDEEL
Initiation interdisciplinaire au deep learning pour le traitement automatique des langues (ideel), projet IReEL vague 2, 2021-2022


# intervenants:
Nicolas Ballier (UFR études anglophones), Guillaume Wisniewski (UFR de linguistique), Jean-Baptiste Yunès (UFR d'informatique)


## Objectifs du cours
> Ce cours vise à la transmission des compétences initiales pour la soumission d’abstract à des conférences dans le domaine des humanités numériques. On cherchera à décrire les problématique linguistiques et les jeux de données envisagés pour les analyser, décrire ces données et établir les traitements automatiques nécessaires. L'idée est notamment de pouvoir initier les étudiants à la traduction automatique dès la L3, en choisissant eux-mêmes leurs textes pour entraîner des réseaux de neurones, s'initier à leur réglage, produire ainsi des "modèles" de traduction neuronale et de juger des traductions produites.
> Ce cours est ouvert aux étudiants en L3 de l'UFR d'études anglophones, de l'UFR de linguistique, de l'UFR d'informatique et de l'UFR de mathématiques et d'informatique.
 

## Fonctionnement
- Les étudiants auront 12 séances de 2h d'enseignement encadré à Paris Diderot au premier semestre (mercredi 13h-15h00, salle 208, bâtiment Olympe de Gouges. Premier cours mercredi 22 septembre).
- Les étudiants travailleront en binôme : un étudiant(e) angliciste de Diderot en L3 (dans le cadre du projet étudiant de L3) ou un étudiant(e) en linguistique informatique  et un étudiant en informatique de Paris Diderot ou de Paris Descartes.
- Les séances alterneront entre informatique et linguistique, si possible toutes les semaines.
- Après trois séances introductives, le suivi se fera au plus près des projets conduits par chaque binôme.
- L’enseignement serait effectué en français mais les productions seraient en langue anglaise (abstract de conférence, blog, poster et article collectif final).
- Les étudiants sont invités à suivre également, en auditeurs libres, le cours de L3 de M. de Guillaume Wisniewski d'initiaton au TAL (traitement automatique du langage) pour approfondir leurs connaissances. Il aura lieu le mercredi de 10h20 à 12h30 en salle 309 au bâtiment Olympe de Gouges (premier cours le 29 septembre 2019). 


## PROGRAMME PREVISIONNEL
=========================

### Séance 1 (22 sept 2021) : les domaines de la linguistique et les principales applications du TAL\ 
présentation des intervenants, du projet , de l'évaluation, quelques outils collaboratifs de la recherche :  (Google Scholar) , le format BibTeX , zotero, overleaf, arxiv, HAL ,

Exemples d'annotation en TAL: la suite coreNLP de Stanford
<https://corenlp.run/>
<https://github.com/nballier/IDEEL/blob/main/Presentation%20IDEEL%20e%CC%81tudiants%20L3.pdf>

- le programme "Initiation à la Recherche  En Licence"
- le pilotage top-down de la recherche (du projet financé à l'exécution de tâches, 'Work Packages')
- une approche de la recherche bottom-up (la problématique de recherche comme rencontre)
- le cycle de production de la recherche scientifique
-  constuire une bibliographie : Google Scholar <https://scholar.google.fr/> 
- gérer une bibliographie  : zotero  (Bibtex, le format bibliographique)
- initiation au latex: le site collaboratif <overleaf.com>
- la soumission à une conférence (notion de relecture par les pairs)
<https://jep-taln2020.loria.fr/conference-virtuelle/articles/apprenti-e-s-chercheur-e-s/>
- la soumission sur arxiv
- les dépôts scientifique et la Science ouverte le site HAL
- Un exemple de dépôt sur HAL (Science ouverte) <https://hal.archives-ouvertes.fr/hal-03212651v1>
<https://hal.archives-ouvertes.fr/hal-03212651/file/JEP-TALN-RECITAL-2020_paper_205.pdf>
- Exemples d'annotation en TAL: la suite coreNLP de Stanford
<https://corenlp.run/>
- l'annotation POS (les jeux d'étiquettes pour l'anglais)
- l'analyse en arbres (parsing)
- l'analyse en dépendance (UD)
- l'analyse de sentiment
- l'analyse de la coréférence
- topo sur les domaines linguistiques, de la phonétique à la pragmatique
- présentation condensée de certaines procédures en TAL : approche de la sémantique par décomposition en tâches de la compréhension
- Table 3: A selection of tests for Machine Comprehension
Ribeiro et al. 2020 Beyond Accuracy: Behavioral Testing of NLP Models with CheckList <https://arxiv.org/abs/2005.04118>
- Tour de table étudiants et première esquisse des projets.


### SEANCE 2 (29 sept 2021) : organiser le repas de cohésion
- tour de table étudiant
- le paradigme 'learning-by-doing'
- la reproductibilité des expériences : atelier REPROLANG
<https://lrec2020.lrec-conf.org/en/reprolang2020/selected-tasks/> 
les principes  FAIR : Findable, Accessible, Interoperable, Reusable
- le réseau social des programmeurs : <github.com>
<https://github.com/guillaume-wisniewski>
- le dépôt des données, des scripts 
<https://github.com/neuroviz/>
- petite introduction à la morphologie computationnelle
- NMT101 : petite recette pour découvrir la TAN (Traduction Automatique Neuronale) avec le site multitraiNMT et un compte gmail :  <https://ntradumatica.uab.cat> 

### séance 3 (6 oct) :  initiation à python /initiation aux carnets jupyter  

Lien vers le cours <https://github.com/nballier/RELIA/blob/master/Python-Initiation.pdf>  
L'objectif est d'arriver à des carnets jupyter et à des scripts simples comme ceux-ci:
mBART
<https://github.com/nballier/SPECTRANS/blob/main/WMT21/mbart_translation.py>  

Hugging Face
<https://github.com/nballier/SPECTRANS/blob/main/WMT21/baseline_translator.py>

Pour la suite, nous verrons des carnets jupyter 
pour OpenNMT sur collab, application que vous avez dans Google Drive

<https://colab.research.google.com/drive/1Circneo7Fan-SAE0G0e6fre2seQWyP9O>
pour JoeyNMT sur collab
<https://colab.research.google.com/drive/1tjmjBJJxqs392X9LSN2X3BHYJNIJlHFl>

pour info, une learning curve possible pour python
<https://github.com/nballier/RELIA/blob/master/4.%20Learning_Python.Rd> 

Pour tester son code python en ligne
<https://www.onlinegdb.com/online_python_debugger>
<https://extendsclass.com/python-tester.html> 


Pour installer l'application pour les carnets jupyter:
<https://github.com/jupyterlab/jupyterlab-desktop#download>



### séance 4 (13 oct) :  initiation à python 2 : les carnets jupyter 
quelques bibliothèques python (NLTK) / lancer des expériences sur un carnet jupyter
- Python 1 : <https://yunes.informatique.univ-paris-diderot.fr/wp-content/uploads/cours/RELIA/2021/Python-Initiation.pdf>
- Python 2 : <https://yunes.informatique.univ-paris-diderot.fr/wp-content/uploads/cours/RELIA/2021/Python-Initiation2.pdf>
- les expressions régulières : <https://yunes.informatique.univ-paris-diderot.fr/wp-content/uploads/cours/RELIA/2021/regexp.pdf>
- Carnets Jupyter : <https://yunes.informatique.univ-paris-diderot.fr/wp-content/uploads/cours/RELIA/2021/Jupyter.pdf>
- Résolution de problème: <https://yunes.informatique.univ-paris-diderot.fr/wp-content/uploads/cours/RELIA/2021/Probleme.pdf>
- la bibliothèque NLTK : <https://yunes.informatique.univ-paris-diderot.fr/wp-content/uploads/cours/RELIA/2021/nltk.pdf>

### séance 5  (20 oct) :  choix du projet, bibliographies, le genre de l'abstract 
LSA models for abstracts <https://www.linguisticsociety.org/resource/model-abstracts>
ACL anthology <https://aclanthology.org/>


### séance 6  (27 oct) :  choix du projet (suite), l'abstract, premiers travaux (procédures d'évaluation) 
- LaTeX : <https://fr.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes>
- outil collaboratif <ttps://www.overleaf.com>
<https://www.overleaf.com/project/617949eb2203f8b639213acc>
- pour générer des tableaux facilement : <https://www.tablesgenerator.com/>
- Feuille de style à suivre pour l'abstract <https://coling2020.org/coling2020.zip>
- See examples of abstracts here: https://www.linguisticsociety.org/resource/model-abstracts



### READING WEEK
Take advantage of Nov 3rd talk:  
3 November 2021, Promises and challenges of massive-scale AI - the case of large language models
Promises and challenges of massive-scale AI – the case of large language models
<https://u-paris.fr/diip/diip-seminars/>


### séance 7 (10 nov) : commentaire des abstracts
<https://coling2020.org/coling2020.zip>
-> commentaire des procédures d'évaluation 
-> préparation des données d'entraînement

quelques bibliothèques python / lancer des expériences sur un carnet jupyter

### séance 8 (17 novembre)  : de l'abstract au poster
un gabarit (template) de poster possible
<https://github.com/nballier/IDEEL/blob/main/Poster%20PAC2021%20template.zip>

### séance 9  (24 novembre) : les procédures de validation de vos expériences

lancer des expériences sur un serveur

### séance 10 : (1er décembre) supervision des expériences et interprétation des résultats 
- l'analyse en dépendances: principes, format d'annotation et corpus d'entraînements:
- le format CONNL-U <https://universaldependencies.org/format.html>
- l'exemple du corpus SEQUOIA <https://github.com/UniversalDependencies/UD_French-Sequoia/blob/master/fr_sequoia-ud-dev.conllu>
-  les bbliothèques de python pour l'annotation en dépendance au format CONNL: exemple: UDpipe
-  UDpipe <https://universaldependencies.org/tools.html#udpipe>
-  exemple en ligne : <https://lindat.mff.cuni.cz/services/udpipe/>
-  les infrastructures de recherche : CLARIN <https://www.clarin.eu/>
HUMA-NUM <https://www.huma-num.fr/> 
- les problématiques du plagiat et de l'autocitation:
<https://www.ox.ac.uk/students/academic/guidance/skills/plagiarism> 

-  save the date: le GGF Tour 9 décembre
Pour ceux et celles qui veulent tout savoir sur la
    Grande Grammaire du français
    https://www.actes-sud.fr/catalogue/litterature/la-grande-grammaire-du-francais

    Et qui n’ont pas pu venir à la journée du 19 novembre à l’Université de Paris
    http://www.llf.cnrs.fr/fr/node/6900

    - le 9 décembre à la BNF, à partir de 18h30, avec Eddy de Preto
    https://www.bnf.fr/fr/agenda/la-grande-grammaire-du-francais
-  save the date : CSSP 9-11 décembre 

Le Quatorzième Colloque de Syntaxe et Sémantique à Paris (CSSP)
aura lieu cette année du 9 au 11 décembre en version hybride : sur
zoom et dans l'amphithéâtre Buffon de l'Université de Paris, 75013.

Vous trouverez le programme à l'adresse suivante:
http://www.cssp.cnrs.fr/cssp2021/programme/index.html

L'inscription se fera en ligne, à l'adresse suivante:
http://www.cssp.cnrs.fr/cssp2021/inscription/inscription.php

### séance 11 : interprétation des résultats et réalisation du poster

### séance 12 : finalisation poster 


14 janvier 2022 : 9h-11h30  : présentation des posters aux étudiants de M2 du master MLDS, rue des Saints-Pères 


## idées de projet 2021-2022
-> construire un modèle de traduction neuronale pour (essayer de) traduire Shakespeare\
-> construire un traducteur automatique d'un texte en français en écriture inclusive\
-> reproduire une expérience précédente: tester ses résultats à partir d'un article décrivant l'expérience, des données, voire du code...\
Exemples de tâches proposées pour l'atelier REPROLANG2020 : <https://lrec2020.lrec-conf.org/en/reprolang2020/selected-tasks/> 



## Quelques exemples de projets choisis de 2019-2020: 
- générer un texte de rap avec un système de contraintes rythmiques  
- un système de résumé automatique pour les romans ?
- comparaison des agents conversationnels (chatbots)
- peut-on détecter automatiquement les mots d'un dictionnaire du XVIIIe siècle devenus obsolètes?  
- peut-on étiqueter les mots à la manière de Walker, lexicographe du XVIIIe siècle?
 
 
## Pour en savoir plus
- retrouvez les archives de la promo 2019-2020:  <http://yunes.informatique.univ-paris-diderot.fr/accueil/enseignement/ireel-relia>
- témoignage d'étudiants et d'enseignants en 2019-2020 sur cet enseignement interdisciplinaire : <https://youtu.be/nokwdPdj3Xc> 
- article instutionnel sur la promo 209-2020 
<https://u-paris.fr/vers-linterdisciplinarite-des-formations/>
 


## document de présentation du  projet à destination des étudiants de L3



LCA5Y260 Projet encadré (code de l'UFR études anglophones)   3 crédits ects

·       Initiation au deep learning pour le traitement automatique des langues

Ce cours d’initiation à la recherche à partir de l’initiation au langage de programmation Python, en collaboration avec l’UFR d’informatique et de Linguistique, aura lieu à Olympe de Gouges le mercredi de 13h00 à 15h00, sur douze semaines. Les étudiants réaliseront en binôme avec un(e) étudiant(e) en informatique ou en linguistique informatique un petit projet d’analyse automatique du langage sur des problématiques linguistiques de l’anglais. En particulier, on montrera quelques applications des réseaux de neurones, telles que la traduction automatique neuronale. Les travaux seront présentés sous forme de posters à des étudiants de master spécialistes du domaine au tout début du semestre suivant.

Pré́-programme des séances et informations complémentaires en :
https://github.com/nballier/IDEEL/
Ce cours bénéficie d’un soutien de l’Université de Paris dans le cadre de l’appel à projets « Initiation à la REcherche En Licence » (IREEL) et permettra aux étudiants d’assister à une conférence.

• Modalités d'évaluation du contrôle continu, session 1 : Les étudiants rédigeront un abstract et un poster présentant leur projet.
• Modalités d'évaluation du contrôle terminal, session 1 : Les étudiants rédigeront un abstract et un poster présentant leur projet.

• Modalités d'évaluation, session 2 : Reprise du poster présentant le projet.

Bibliographie :

Bird, S., Klein, E., & Loper, E. (2009). Natural language processing with Python: analyzing text with the natural language toolkit. O'Reilly

# Webographie :
<https://github.com/nballier/IDEEL>


# FETE DE LA SCIENCE 2021 !!

Pour sinscire à la table-ronde sur la recherche du 1er octobre 20221 (14h-15h , 15h30-16h30) :
<https://www.eventbrite.com/e/inscription-table-ronde-les-metiers-de-la-recherche-171867078057>

 ![alt text](https://github.com/nballier/IDEEL/blob/main/TableRondeFeteDeLaScience.pdf)
 


# Acknowledgement

This project was supported by IdEx Université de Paris ANR-18-IDEX-0001 (AAP Initiation à la Recherche en Licence, vague 2)
<https://u-paris.fr/resultats-de-laap-ireel-vague-2/>

 ![alt text](https://github.com/nballier/IDEEL/blob/main/Logo_Idex_IA.pdf)
