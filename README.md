# estia-2a-TAI
projet  TAI
[Etape 1] [1C-1STP]
Concevoir théoriquement une partie d'un outil de gestion de données industrielles générique qui permette de représenter un processus interne à une entreprise. Chaque groupe a une fonctionnalité différente.

A l’issue de cette étape le groupe sera en mesure de fournir un dossier de conception avancée (DCA), qui se décomposera en  (et uniquement en) :

    un diagramme des cas d’utilisation avec au minimum 3 acteurs [REF.1]
    le diagramme de séquences correspondant [cf module "Cycle de vie du produit", matière "Génie logiciel"]  [VOIR REF.4]
    les vues = interfaces graphiques =  IHM  (sous WireFrame Balsamiq de préférence) [REF.2][REF.3] avec les fonctionnalités attendues sous-jacentes.

Conseils :

    Appliquer la méthode vue en Ingénierie de Projet
    On se placera du point de vue de l'utilisateur.

[Etape 2]   [1TD]

Vous devez déposer sous Moodle votre DCA au plus tard  le 8 mars 2023 à 18:00 en pdf.

Il sera validé, ou non validé, par les chargées de TD avant la séance de TD. Le DCA doit recevoir 2 validations. Une validation par les chargés de TD MÉTIERS (Mrs Bastres, Dulin et Requillard) + une validation par les chargés de TD INFORMATIQUE (N. Coutire et E. Bouzekri). Ces 2 validations apparaitront sous moodle avec commentaires + une note sur 100.

Pendant la séance de TD :

- si validé : le groupe fera la conception de sa Base de Données [cf. cours de première année en BdD dans le module Systèmes Informatiques] et en s'aidant du document de cette page Moodle "Consignes pour la réalisation de la base de Données". 

- si non validé : le groupe discutera sa solution avec les chargés de TD pour faire évoluer son analyse et son DCA.

[Etape 3][6TP-xSTP]
La fonctionnalité de l’[étape 2] sera implémentée dans un contexte d'application distribuée.
Pour le développement les outils suivants sont imposés :

- MySQL  en tant que SGBD, sera accédé via phpMyAdmin

- HTML pour l’interface graphique, incluant des balises JSTL (Java server page Standard Tag Library) pour la création de pages Web dynamiques .

- Le serveur Tomcat pour la communication entre les pages Web et le programme Java.

- JAVA EE (Java Enterprise Edition) pour le développement de l’application

- JDBC pour l’interface entre JAVA et la BdD

Evaluation en Contrôle Continu :

Chaque étape sera validée par les chargés de TD et TP. Il est de votre responsabilité de montrer à votre professeur où vous en êtes au fur et à mesure que les étapes vous sembles atteintes sans attendre le dernier TP semaine 18 de 2023  

Ainsi vous passerez de F à E à D à C à B et à A ... je l'espère pour tous les groupes !

Formule de notation : CdC de l'étape 2 + BdD + IG + MVC + Code + JDBC + FonctionneEtConformeAuCdC =  grade > F

sinon F.

Le rattrapage (session 2) le 11 mai  2023  = sujet identique mais : plus simple/court, imposé, en temps surveillé et seul.
