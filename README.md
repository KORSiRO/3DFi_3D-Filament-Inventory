<h1 align="center">3DFi 3D Filament Inventory</h1>

<p align="center">  
  <img src="https://github.com/user-attachments/assets/31af8efe-ef62-400f-9212-5ce13b734101"/>  
</p>

3DFi est un tableau Excel vous permettant de suivre vos consommations en filament 3D.  
Plusieurs valeurs sont prises en compte pour vous permettre d'être le plus précis possible. 

  > [!NOTE]
>* *Ce tableau est composé de 12 colonnes et 2 feuilles qui ont chacune un rôle important.*

 <img src="https://github.com/user-attachments/assets/00fee29d-f7b0-4838-9b5b-6ab21d8734ef"/> 


<h2 align="center">Quelles valeurs sont prises en compte ?</h2>  
  

<h3 align="center"><ins>1. "Quantité de bobine(s) :</ins></h3>  

   Présente pour renseigner le nombre de bobines identiques pour une même ligne.

<h3 align="center"><ins>2. "Poids total de(s) bobines neuves (g)" :</ins></h3>

   Présente pour renseigner le poids total en grammes du ou des bobines identiques pour une même ligne.
   > <ins>Ex :</ins> si vous avez dans votre inventaire 3 bobines de filament noir de marque Bambu Lab de 1kg chacune, renseignez "3000g"
   
<h3 align="center"><ins>3. "Type de Filament" et "Marque de filament" :</ins></h3>  

<p align="center">  
<img src="https://github.com/user-attachments/assets/399afa3a-1b1d-4af3-8b2e-de2667a24441"/>
</p>  

  
Ces 2 colonnes contiennent 2 listes : "**Type de Filament**" et "**Marque de Filament**".  
Les sources de ces listes sont disponibles dans la feuille "**Matériaux**".  
Elles contiennent déjà plus de **150 données préenregistrées**.

<p align="center">  
<img src="https://github.com/user-attachments/assets/adbec5de-0775-45d9-8917-beb034a8c579"/>
</p>  

Ces listes peuvent être modifiées afin d'y ajouter un(e) ou plusieurs types/marques de filament.  
Il suffit d'ajouter dans la colonne correspondante ce que vous souhaitez afin de pouvoir ensuite le retrouver dans la liste de la colonne correspondante sur la feuille "**Inventaire**".

<h3 align="center"><ins>4. "Couleurs" :</ins></h3>  

  Vous l'aurez compris, cette colonne-ci assure la prise en charge de la couleur du filament.  

<h3 align="center"><ins>5. "Poids restant" :</ins></h3>  

Cette colonne permet d'obtenir le poids restant d'une bobine avec la prise en compte de 2 valeurs :  
- Le "Poids total de(s) bobines neuves (g)"
- La "Nouvelle consommation de filament en (g)"

  > <ins>Ex :</ins> Si vous renseignez sur la première ligne 1 bobine de 1000g (neuve) et que vous souhaitez déduire la quantité de filament utilisée par une impression en cours dans la colonne "Nouvelle consommation de filament en (g)",
  > une soustraction automatique est effectuée dans la colonne "Poids restant" pour vous donner un résultat le plus précis possible de la quantité restante.

<h3 align="center"><ins>6. "Lieu de stockage" :</ins></h3>  

Facilite la recherche de vos bobines si elles sont entreposées à différents endroits de votre atelier, bureau ou pièce dédiée.  

<h3 align="center"><ins>7. "TD (Hueforge)" :</ins></h3>

La TD ou Transmission Distance de HueForge est un nombre indiquant la quantité de lumière que le filament laisse passer.  
Utile si vous imprimez souvent des Hueforge d'avoir cette valeur rapidement sous les yeux en fonction du filament utilisé.

<h3 align="center"><ins>8. "Temps de séchage (mins)" :</ins></h3>  

Comme pour "TD (Hueforge) c'est une valeur qu'il est intéressant d'avoir sous les yeux rapidement quand vous en avez besoin.

<h3 align="center"><ins>9. "Alerte" et "% restant" :</ins></h3>  

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
> 
