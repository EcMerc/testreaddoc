Données
=======

Bienvenue sur le git du Parc national du Mercantour.

`Première fois sur git ? Cliquez ici <./tutos/git.md>`__

Vous trouverez ici un `dépôt (qu’est-ce que c’est
?) <./tutos/README.md##dépôt-repository>`__ contenant la documentation
et les codes concernant la `base de données (qu’est-ce que c’est
?) <./tutos/README.md##base-de-données>`__ utilisée par les agents du
parc. Ainsi que des tutoriels et ressources facilitant l’utilisation de
la base de données, et des ressources géographiques en général.

Ce dépôt
========

Ce dépôt est composé de deux parties principales qui vous seront utiles.
`bd_pnm <#bd_pnm>`__ contient les descriptions des schémas et données de
la base de données du parc, `tutos <#tutos>`__ contient les tutoriels,
supports de formations et ressources pour l’utilisation de QGIS et des
bases de données du parc.

## `bd_pnm <./bd_pnm>`__

Dans ce dossier, se trouve la documentation permettant de comprendre le
contenu de chaque `schéma (qu’est-ce que c’est
? <./tutos/README.md#schéma>`__) de la base de données, ainsi que les
[*projets qgis*]((./tutos/README.md#projet ) associés et les requêtes
sql d’intérêt.

Le dossier `bn_pnm <./bd_pnm>`__ contient un dossier par
`schéma <./tutos/README.md#schema>`__. Chaque dossier-schéma contient: -
un fichier README.md détaillant le contenu et l’utilité du schéma - un
dossier “projets_qgis” contenant les projets_qgis validés en format
texte (téléchargeables et utilisables par les agents). *NB: Les projets
ne sont pas directement visionnables depuis git, il est nécessaire de
les télécharger pour ensuite les ouvrir avec Qgis.* - un dossier “sql”
contenant les requêtes sql utiles à ce schéma - un dossier “bin” à
l’usage des gestionnaires de la base de données

Le dossier “\_modele” contient le modèle de la documentation appliquée à
chaque schéma.

*les noms des schémas ci-dessous sont des liens cliquables*

+-----------------------------------+-----------------------------------+
| Schéma                            | Description des données           |
+===================================+===================================+
| `admin_ex                         | Données concernant les limites    |
| press <./bd_pnm/admin_express>`__ | administratives (produites par    |
|                                   | l’IGN)                            |
+-----------------------------------+-----------------------------------+
| `ag_pasto <./bd_pnm/ag_pasto>`__  | Agropastoralisme                  |
+-----------------------------------+-----------------------------------+
| `bd_lacs <./bd_pnm/bd_lacs>`__    | Données concernant les lacs       |
+-----------------------------------+-----------------------------------+
| `cadastre <./bd_pnm/cadastre>`__  | Données publiques issues cadastre |
+-----------------------------------+-----------------------------------+
| `charte <./bd_pnm/charte>`__      | Données nécessaires à la          |
|                                   | réalisation de la carte des       |
|                                   | vocations                         |
+-----------------------------------+-----------------------------------+
| `foret <./bd_pnm/foret>`__        | Données publiques issues cadastre |
+-----------------------------------+-----------------------------------+
| `geonature_synthese               | Observations géonature,           |
|  <./bd_pnm/geonature_synthese>`__ | détaillées et agrégées selon      |
|                                   | différents critères               |
+-----------------------------------+-----------------------------------+
| `geotrek <./bd_pnm/geotrek>`__    | Sentiers du parc                  |
+-----------------------------------+-----------------------------------+
| `inpn <./bd_pnm/inpn>`__          | Limites de parcs nationaux,       |
|                                   | régionaux, et réserves naturelles |
+-----------------------------------+-----------------------------------+
| `limites <./bd_pnm/limites>`__    | Limites du parc et                |
|                                   | administratives                   |
+-----------------------------------+-----------------------------------+
| `rice <./bd_pnm/rice>`__          | Réserve Internationale de Ciel    |
|                                   | Etoilé                            |
+-----------------------------------+-----------------------------------+
| `survol <./bd_pnm/survol>`__      | Zones sensibles en lien avec les  |
|                                   | autorisations de survol           |
+-----------------------------------+-----------------------------------+
| `tourisme <./bd_pnm/tourisme>`__  | Tourisme et fréquentation du parc |
|                                   | (compteurs..)                     |
+-----------------------------------+-----------------------------------+

## `tutos <./tutos>`__

Le dossier `tutos <./tutos>`__ contient l’ensemble des tutoriels et
guides pour l’accès et la bonne utilisation des données géographiques du
aprc, et provenant de sources externes. Ainsi qu’un glossaire des termes
de géomatique ou en lien avec ce dépôt, et une F.A.Q. qui a vocation à
intégrer vos interrogations !

Si vous venez de recevoir votre ordinateur, il est nécessaire de
réaliser les premiers paramétrages pour avoir accès à la base de données
du parc, et aux fonds de carte au format wms.
`ajout_fond_de_carte_wms <./tutos/ajout_fond_de_carte_wms.md>`__

+-----------------------------------+-----------------------------------+
| Nom                               | Description                       |
+===================================+===================================+
| `ajout_fond_de_carte_wms <./tut   | Ajouter un fond de carte standard |
| os/ajout_fond_de_carte_wms.md>`__ | (SCAN25, Orthophotos) à partir    |
|                                   | d’un `service wms <#wms>`__       |
+-----------------------------------+-----------------------------------+
| `ajout_fond_SCAN25                | Ajouter le fond SCAN25 à partir   |
| <./tutos/ajout_fond_SCAN25.md>`__ | d’un `service wms <#wms>`__       |
+-----------------------------------+-----------------------------------+
| `bonnes_pratiques                 | Rappel des bonnes pratiques pour  |
|  <./tutos/bonnes_pratiques.md>`__ | le travail informatique et sur    |
|                                   | QGIS                              |
+-----------------------------------+-----------------------------------+
| `editer_des_polygones <./         | Édition de données vecteurs pour  |
| tutos/editer_des_polygones.md>`__ | modifier/ajouter des entités ou   |
|                                   | attributs                         |
+-----------------------------------+-----------------------------------+
| `empaqueter_un_projet <./         | Enregistrer la symbologie d’un    |
| tutos/empaqueter_un_projet.md>`__ | projet et l’ensemble des couches  |
|                                   | associées dans un seul fichier    |
+-----------------------------------+-----------------------------------+
| `FAQ <./tutos/FAQ.md>`__          | Solutions aux questions et        |
|                                   | problèmes les plus fréquents      |
+-----------------------------------+-----------------------------------+
| `filtres <./tutos/filtres.md>`__  | Comprendre l’utilisation des      |
|                                   | filtres pour ne charger qu’une    |
|                                   | partie des entités d’une couche   |
+-----------------------------------+-----------------------------------+
| `generer_un_atlas                 | Générer un ensemble de cartes à   |
|  <./tutos/generer_un_atlas.md>`__ | partir d’une couche               |
+-----------------------------------+-----------------------------------+
| `git <./tutos/git.md>`__          | Présentation et explication de ce |
|                                   | qu’est “git”                      |
+-----------------------------------+-----------------------------------+
| `glossaire                        | Glossaire des principaux termes   |
|  <./tutos/README.md#glossaire>`__ | de géomatique utilisés sur ce git |
+-----------------------------------+-----------------------------------+
| `installation_certificats_bas     | Paramétrage de l’accès à la base  |
| e_de_donnees <./tutos/installer_c | de données depuis QGIS            |
| ertificats_base_de_donnees.md>`__ |                                   |
+-----------------------------------+-----------------------------------+
| `mon_premier_projet <             | Tutoriel complet sur la           |
| ./tutos/mon_premier_projet.md>`__ | consultation d’un projet QGIS     |
|                                   | existant, son enregistrement, sa  |
|                                   | modification et ses exports       |
+-----------------------------------+-----------------------------------+
| `premier_paramétrage <.           | Configuration de base de QGIS     |
| /tutos/premier_parametrage.md>`__ | permettant d’en assurer le bon    |
|                                   | fonctionnement                    |
+-----------------------------------+-----------------------------------+
| `ressour                          | Liste et description des          |
| ces_geographiques_wms <./tutos/re | ressources disponibles au format  |
| ssources_geographiques_wms.md>`__ | wms.                              |
+-----------------------------------+-----------------------------------+

## Structure du dépôt

.. code:: bash

   donnees
   ├───bd_pnm
   │   │
   │   ├───ag_pasto
   │   │   ├───projets_qgis
   │   │   ├───sql
   │   │   └───bin
   │   │
   │   ├───geonature_synthese
   │   │   ├───projets_qgis
   │   │   ├───sql
   │   │   └───bin
   │   ├───limites
   │   │   ├───projets_qgis
   │   │   ├───sql
   │   │   └───bin
   │   │
   │   ├─── ....
   │   │   │
   │   │   ├───projets_qgis
   │   │   ├───sql
   │   │   └───bin
   │   │
   │   │
   │   └───_modele
   │       ├───projets_qgis
   │       ├───sql
   │       └───bin
   │ 
   │ 
   └───tutos
       ....

--------------

Maintenance et utilisateurs avancés
-----------------------------------

Mise à jour
~~~~~~~~~~~

| Dans chaque dossier-schéma se trouve un dossier bin contenant
  notamment deux scripts: - ``dump_schema`` lit depuis la base de
  données la version courante du schema sql et l’enregistre dans
  ``schema.sql``.
| - ``dump_project`` télécharge la version courante du projet QGIS
  depuis la base de données et l’enregistre dans ``nom_du_schema.qgs``


**Lumache** (/lu'make/) is a Python library for cooks and food lovers
that creates recipes mixing random ingredients.
It pulls data from the `Open Food Facts database <https://world.openfoodfacts.org/>`_
and offers a *simple* and *intuitive* API.

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
