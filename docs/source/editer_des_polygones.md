# Edition de polygones.


## Explications

Dans une couche au format [vecteur](./README.md#vecteur), il est possile de modifier ou d'ajouter des entit�s. 
Qgis permet de le faire en passant par le mode �dition. 
Nous verrons ici comment cr�er une nouvelle couche vide, puis y cr�er des entit�s. Une fois les
entit�s cr��es, on peut facilement en modifier la g�om�trie ou les attributs. 

Il n'est possible de cr�er/modifier des entit�s que dans des couches dont vous �tes propri�taires. C'est-�-dire ou
bien des couches issues de fichiers enregistr�s localement dans votre ordinateur, ou bien d'un serveur ou vous �tes identifi�e
et disposez des droits de cr�ation/modification. 


Attention, une fois une modification enregistr�e, il n'est pas possible de revenir en arri�re.

<!--Ce tutorial d�taille les �tapes permettant de configurer l'acc�s au catalogue de donn�es WMS/WFS du Parc national du Mercantour.
Il exige d'avoir re�u au pr�alable un fichier zip du service informatique du Parc. --> 
Dans ce tuto, on cr�e une couche au format GeoPackage. Ce format ouvert et non-propri�taire pr�sente l'avantage de ne contenir qu'un fichier (contrairement au shapefile) 
et s'ouvre facilement avec QGIS. 

 
 
## Pas � pas

### Cr�er une nouvelle couche. 
- Dans la barre des menus, Cliquer sur "Couche > Cr�er une couche > Nouvelle couche GeoPackage"
<img src="./img/creer_couche.png" alt= �� width="50%" height="50%"> 

- Dans la fen�tre qui s'affiche, cliquer sur l'ic�ne "..." pour renseigner l'emplacement o� le fichier sera enregistr�.
<img src="./img/pitits_points.png" alt= �� width="30%" height="30%"> 

- Renseigner le type de g�om�trie selon le type d'usage voulu. Dans la plupart des cas: "Point", "Polyligne" ou "Polygone".
- Ne pas oublier d'indiquer la projection si elle est demand�e: "EPSG:2154 - RGF v1 / Lambert-93"
- Si n�cessaire, ajouter des champs. Il sera toujours possible d'en ajouter plus tard. 


### Activer le mode �dition

- Activer le mode �dition (2 fa�ons possibles).

    M�thode 1 (_Recommand�_):  S�lectionner la couche � modifier, puis cliquer sur l'ic�ne de crayon dans la barre d'outils en haut de l'�cran  
<img src="./img/mode_edition.png" alt= �� width="50%" height="50%"> 
	
    M�thode 2 :Cliquer droit sur la couche � modifier, puis en cliquant sur l'ic�ne crayon "Basculer en mode �dition"
<img src="./img/modeedition_parcouche.png" alt= �� width="50%" height="50%"> 

- Une fois dans ce mode, un crayon apparait au-dessus du symbole de la couche..
<img src="./img/couche_en_cours_edition.png" alt= �� width="50%" height="50%"> 


- ..et des outils deviennent accessibles dans la barre d'outil. Ces outils sont regroup�s dans les barres d'outils "Num�risation" et "Num�risation avanc�e".


- On peut afficher ces outils (s'ils n'apparaissent pas)  en faisant un clic droit sur une des barres d'outils en haut de l'�cran, ou bien dans la barre de menu "Vue > Barres d'outils > ..."

<img src="./img/barre_doutils_numerisation.png" alt= �� width="50%" height="50%"> 

_A partir de l�, diff�rentes op�rations sont disponibles, nous ne d�crirons que les plus simples._

### Cr�er une nouvelle entit�

- Proche de l'icone de crayon, dans la barre d'outils, se trouve l'ic�ne "Ajouter une entit�"

<img src="./img/edition_ajouter_une_entite.png" alt= �� width="50%" height="50%"> 

- Apr�s avoir cliqu� dessus, votre curseur change. Vous pouvez directement ajouter des points qui formeront, suivant le type de g�om�trie que votre couche contient
	- une entit� par point
	- une partie de ligne ou de polygone
- Un clic gauche vous permet d'ajouter un point, un clic droit termine la saisie d'une entit� sans en rajouter de nouveau, _donc pour faire un rectangle, il faut 4 clics gauches + 1 clic droit_.
- A chaque fin de saisie, une boite de dialogue s'ouvre, permettant d'entrer manuellement les attributs de l'entit�. Dans la plupart des cas, vous n'�tes pas oblig� d'entrer
quoi que ce soit, et pouvez simplement cliquer sur OK pour continuer la saisie. 

<img src="./img/nouvelle_entite.png" alt= �� width="50%" height="50%"> 



### Modifier la g�om�trie d'une entit� existante

- L'outil sommet, disponible dans la barre d'outil num�risation � droite de l'outil d'ajout d'entit� permet d'ajouter, supprimer, ou cr�er de nouveaux sommets.
<img src="./img/outil_sommet.png" alt= �� width="50%" height="50%"> 
- Une fois l'outil sommet s�lectionn�, on peut s�lectionner n'importe quel sommet en cliquant dessus. Les sommets de chaque polygone sont visibles sous la forme de petits cercles rouges

<img src="./img/edition_modif_de_sommets.png" alt= �� width="50%" height="50%"> 

- Apr�s avoir s�lectionn� un sommet avec l'outil sommet, il est possible de le supprimer en appuyant sur la touche "Suppr" du clavier. 
- On peut aussi le d�placer, en cliquant � nouveau avec le clic gauche � un autre endroit apr�s avoir s�lectionn� un sommet. 

- Enfin, il est possible de cr�er de nouveaux sommets dans un polygone en cliquant tr�s pr�cis�ment sur la croix qui apparait en faisant passer le curseur entre deux sommets. 
<img src="./img/edition_nouveau_sommet.png" alt= �� width="50%" height="50%"> 

En combinant le d�placement, la modification, et la cr�ation de sommets, il est possible de changer compl�tement la forme d'un polygone.

_Tant que les modifications n'ont pas �t� enregistr�es, elles ne sont pas d�finitives_


### Supprimer une entit�

- Une fois dans le mode �dition, il est aussi possible de supprimer compl�tement une entit� en la s�lectionnant avec l'outil de s�lection, puis en appuyant sur la touche suppr.
<img src="./img/selection_entite.png" alt= �� width="50%" height="50%"> 



### Modifier les attributs d'une entit�

- Une fois activ� l'outil �dition, il est possible d'�diter � la main les cases de la table attributaire. 
_On peut aussi activer le mode �dition depuis la barre d'outils de la table attributaire._
<img src="./img/mode_tableattributaire.png" alt= �� width="50%" height="50%"> 




