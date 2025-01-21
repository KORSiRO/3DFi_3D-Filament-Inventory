<h1 align="center">3DFi - 3D Filament Inventory</h1>

<p align="center">  
  <img src="https://github.com/user-attachments/assets/31af8efe-ef62-400f-9212-5ce13b734101"/>  
</p>

<br />

3DFi est un tableau Excel vous permettant de suivre vos consommations en filament 3D.  
Plusieurs valeurs sont prises en compte pour vous permettre d'être le plus précis possible. 

<br />

> [!NOTE]
>* *Ce tableau est composé de 12 colonnes et 2 feuilles qui ont chacune un rôle important.*

 <img src="https://github.com/user-attachments/assets/00fee29d-f7b0-4838-9b5b-6ab21d8734ef"/> 

<br /><br />

## <ins>Quelles sont les valeurs prises en compte ?</ins>

<br />

### :curly_loop: <ins>"Quantité de bobine(s)" :</ins>

   Présente pour renseigner le nombre de bobines identiques pour une même ligne.

<br />

### :new: <ins>"Poids total de(s) bobines neuves (g)" :</ins>

   Présente pour renseigner le poids total en grammes du ou des bobines identiques pour une même ligne.
   > <ins>Ex :</ins> si vous avez dans votre inventaire 3 bobines de filament noir de marque Bambu Lab de 1kg chacune, renseignez "3000g"

<br />   

### <ins>"Type de Filament" et "Marque de filament" :</ins>

<p align="center">  
<img src="https://github.com/user-attachments/assets/399afa3a-1b1d-4af3-8b2e-de2667a24441"/>
</p>  

Ces 2 colonnes contiennent 2 listes : "**Type de Filament**" et "**Marque de Filament**".  
Les sources de ces listes sont disponibles dans la feuille "**Matériaux**".  
Elles contiennent déjà plus de **150 données préenregistrées**.

<br />

<p align="center">  
<img src="https://github.com/user-attachments/assets/adbec5de-0775-45d9-8917-beb034a8c579"/>
</p>  
Ces listes peuvent être modifiées afin d'y ajouter un(e) ou plusieurs types/marques de filament.  
Il suffit d'ajouter dans la colonne correspondante ce que vous souhaitez afin de pouvoir ensuite le retrouver dans la liste de la colonne correspondante sur la feuille "**Inventaire**".

<br />

### :art: <ins>"Couleurs" :</ins>

  Vous l'aurez compris, cette colonne-ci assure la prise en charge de la couleur du filament.  

<br />

### :chart_with_downwards_trend: <ins>"Poids restant" :</ins>

Cette colonne permet d'obtenir le poids restant d'une bobine avec la prise en compte de 2 valeurs :  
- Le "Poids total de(s) bobines neuves (g)"
- La "Nouvelle consommation de filament en (g)"

  > <ins>Ex :</ins> Si vous renseignez sur la première ligne 1 bobine de 1000g (neuve) et que vous souhaitez déduire la quantité de filament utilisée par une impression en cours dans la colonne "Nouvelle consommation de filament en (g)",
  > une soustraction automatique est effectuée dans la colonne "Poids restant" pour vous donner un résultat le plus précis possible de la quantité restante.

<br />

### :file_folder: <ins>"Lieu de stockage" :</ins> 

Facilite la recherche de vos bobines si elles sont entreposées à différents endroits de votre atelier, bureau ou pièce dédiée.  

<br />

### :flower_playing_cards: <ins>"TD (Hueforge)" :</ins>

La TD ou Transmission Distance de HueForge est un nombre indiquant la quantité de lumière que le filament laisse passer.  
Utile si vous imprimez souvent des Hueforge d'avoir cette valeur rapidement sous les yeux en fonction du filament utilisé.

<br />

### :clock130: <ins>"Temps de séchage (mins)" :</ins>

Comme pour "TD (Hueforge) c'est une valeur qu'il est intéressant d'avoir sous les yeux rapidement quand vous en avez besoin.

<br />

### :warning: <ins>"Alerte" et "% restant" :</ins> 

Ces deux colonnes sont un peu différentes des autres.  
Elles vous indique par un texte et une couleur vive que votre filament est bientôt épuisé.
Aucun besoin de saisir manuellement une valeur, tout est automatisé.  

<p align="center">  
<img src="https://github.com/user-attachments/assets/1b905135-9b02-408d-80f2-acd02d426dd2"/>
</p>

> <ins>Ex :</ins> Si vous renseignez un poids total de bobines neuves pour 1 bobine de 1000g et qu'une impression en cours consomme 200g de filament, alors vous renseignez cette valeur (200g) dans la colonne "Nouvelle consommation de filament en (g)".<br>
> De ce fait, le poids restant sera donc de 800g et sera automatiquement renseigné dans la colonne "Poids restant".<br>
> En parallèle, la cellule "% restant" vous donne donc cette information en comparant la colonne "Poids total de(s) bobines neuves (g)" avec la colonne "Poids restant".<br>
> Quand le poids restant en grammes atteint 30% de la valeur en grammes initiale de la bobine neuve, la ligne complète change de couleur et le texte "⚠️Filament bientôt épuisé" apparait dans la colonne "Alerte".
> Vous donnant ainsi l'information de penser à remplacer sous peu votre bobine. 
