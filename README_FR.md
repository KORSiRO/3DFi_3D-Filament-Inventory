<h1 align="center">3DFi - 3D Filament Inventory</h1>

<br />

<h2 align="center">⬇️ Video du fonctionnement du fichier ⬇️</h2>

[![Watch the video](https://github.com/user-attachments/assets/29f38d4c-c530-4949-a487-fa41f8b59640)](https://youtu.be/bSyMhTsakyI)

<br />

### :arrow_right: [README in English](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README.md)

### ⬇️ [Téléchargement](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/releases)

<br />

3DFi est un tableau Excel vous permettant de suivre vos consommations en filament 3D.  
Plusieurs valeurs sont prises en compte pour vous permettre d'être le plus précis possible. 

<br />

> [!NOTE]
>* *Ce tableau est composé de 16 colonnes et 2 feuilles qui ont chacune un rôle important.*

<br />

### TABLE DES MATIÈRES:
<details>

<summary>Feuille 1 : Inventaire :arrow_down_small:</summary><br>

- :curly_loop: [Quantité-de-bobine(s)](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README.md#curly_loop-quantit%C3%A9-de-bobines-)
- :new: [Poids total de(s) bobines neuves (g)](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#new-poids-total-des-bobines-neuves-g-)
- :memo: [Type de Filament" et "Marque de filament](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#memo-type-de-filament-et-marque-de-filament-)
- :art: [Couleurs](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#art-couleurs-)
- :chart_with_downwards_trend: [Poids restant](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#chart_with_downwards_trend-poids-restant-)
- :file_folder: [Lieu de stockage](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#file_folder-lieu-de-stockage-)
- :flower_playing_cards: [TD (Hueforge)](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#flower_playing_cards-td-hueforge-)
- :clock130: [Temps de séchage (mins)](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#flower_playing_cards-td-hueforge-)
- :fire: [Température Buse/Plateau](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README_FR.md#fire-temp%C3%A9rature-buseplateau)
-  :sweat_drops: [Débit](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README_FR.md#sweat_drops-d%C3%A9bit)
-  :bar_chart: [Facteur K](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README_FR.md#bar_chart-facteur-k)
-  :arrow_heading_down: [Nouvelle consommation de filament](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README.md#arrow_heading_down-nouvelle-consommation-de-filament)
- :warning: [Alerte" et "% restant](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#warning-alerte-et--restant-)
- :black_square_button: [Macro Annuler la modification](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory#black_square_button-macro-annuler-la-modification-)
</details>  

<br /><br />

<h2 align="center">:clipboard: Inventaire</h2>

<p align="center">  
  <img src="https://github.com/user-attachments/assets/7dfce432-5eb8-4d2b-8eec-9790c35aeeca"/>  
</p>

<details>

<summary>Cliquez pour dérouler :arrow_down_small:</summary>


- ### :curly_loop: Quantité de bobine(s)<br>

Présente pour renseigner le nombre de bobines identiques pour une même ligne.

<br />

- ### :new: Poids total de(s) bobines neuves (g)<br>

Présente pour renseigner le poids total en grammes du ou des bobines identiques pour une même ligne.  
  
> <ins>Ex:</ins> si vous avez dans votre inventaire 3 bobines de filament noir de marque Bambu Lab de 1kg chacune, renseignez "3000g"

<br />

- ### :memo: Type de Filament et Marque de filament<br>

<p align="center">  
<img src="https://github.com/user-attachments/assets/399afa3a-1b1d-4af3-8b2e-de2667a24441"/>
</p>  

Ces 2 colonnes contiennent 2 listes : **`"Type de Filament"`** et **`"Marque de Filament"`**  
Les sources de ces listes sont disponibles dans la feuille **`"Matériaux"`**  
Elles contiennent déjà plus de **`150 données préenregistrées`**.

<br />

<p align="center">  
<img src="https://github.com/user-attachments/assets/adbec5de-0775-45d9-8917-beb034a8c579"/>
</p>  

Ces listes peuvent être modifiées afin d'y ajouter un(e) ou plusieurs types/marques de filament.  
Il suffit d'ajouter dans la colonne correspondante ce que vous souhaitez afin de pouvoir ensuite le retrouver dans la liste de la colonne correspondante sur la feuille **`"Inventaire"`**.  

<br />

- ### :art: Couleurs<br>

  Vous l'aurez compris, cette colonne-ci assure la prise en charge de la couleur du filament.  

<br />

- ### :chart_with_downwards_trend: Poids restant (g)<br>

Cette colonne permet d'obtenir le poids restant d'une bobine avec la prise en compte de 2 valeurs :  
- Le **`"Poids total de(s) bobines neuves (g)"`** 
- La **`"Nouvelle consommation de filament en (g)"`** 



  > Ex : Si vous renseignez sur la première ligne 1 bobine de 1000g (neuve) et que vous souhaitez déduire la quantité de filament utilisée par une impression en cours dans la colonne "Nouvelle consommation de filament en (g)",
  > une soustraction automatique est effectuée dans la colonne "Poids restant" pour vous donner un résultat le plus précis possible de la quantité restante.

<br />

- ### :file_folder: Lieu de stockage<br>

Facilite la recherche de vos bobines si elles sont entreposées à différents endroits de votre atelier, bureau ou pièce dédiée.  

<br />

- ### :flower_playing_cards: TD (Hueforge)<br>

La TD ou Transmission Distance de HueForge est un nombre indiquant la quantité de lumière que le filament laisse passer.  
Utile si vous imprimez souvent des Hueforge d'avoir cette valeur rapidement sous les yeux en fonction du filament utilisé.

<br />

- ### :clock130: Temps de séchage (mins)<br>

Comme pour "TD (Hueforge) c'est une valeur qu'il est intéressant d'avoir sous les yeux rapidement quand vous en avez besoin.

<br />

- ### :fire: Température Buse/Plateau<br> 

Ai-je réellement besoin de vous expliquez l'utilité de cette cellule ? :stuck_out_tongue_winking_eye:

<br />

- ### :sweat_drops: Débit<br>

Le **`Débit`** ou **`Flow`** correspond au volume de filament qui traverse l'extrudeur.<br>

<br />

- ### :bar_chart: Facteur K<br>

Pour rappel, le Facteur K est une valeur qui sert à déterminer la vitesse maximale de l’impression tout en limitant les vibrations mécanique.<br>
En d'autres termes, le Facteur K permet d’ajuster l’accélération dans le mouvement des axes pour garantir un bon équilibre entre rapidité et qualité

<br />

- ### :arrow_heading_down: Nouvelle consommation de filament<br> 

Évoqué rapidement dans la partie précédente, la colonne **`"Nouvelle consommation de filament en (g)"`** permet de soustraire automatiquement une consommation de filament d'une impression en cours au poids restant d'une ou plusieurs bobines.<br>
Le dernier poids qui apparaît dans la colonne **`"Poids restant"`** est en mémoire.<br>
Si vous renseignez une **`Nouvelle consommation de filament`** la soustraction continue donc à partir du dernier poids en mémoire.

<br />

> Ex : Si vous renseignez un poids restant de par exemple 800g et qu'une impression prévoit d'utiliser 200g de filament,<br>
> en saisissant la valeur de 200g dans la colonne **`"Nouvelle consommation de filament en (g)"`** le poids restant est automatiquement ajusté (800-200 = 600g restant).<br>*
> Toujours pour vous permettre d'avoir un suivi précis de votre utilisation.

<br />

- ### :warning: Alerte et % restant<br>

Ces deux colonnes sont un peu différentes des autres.  
Elles vous indique par un texte et une couleur vive que votre filament est bientôt épuisé.  
Aucun besoin de saisir manuellement une valeur, tout est automatisé.  

<p align="center">  
<img src="https://github.com/user-attachments/assets/1b905135-9b02-408d-80f2-acd02d426dd2"/>
</p>

<br />

> Ex : Si vous renseignez un poids total de bobines neuves pour 1 bobine de 1000g et qu'une impression en cours consomme 200g de filament, alors vous renseignez cette valeur (200g) dans la colonne "Nouvelle consommation de filament en (g)".<br>
> De ce fait, le poids restant sera donc de 800g et sera automatiquement renseigné dans la colonne "Poids restant".<br>
> En parallèle, la cellule "% restant" vous donne donc cette information en comparant la colonne "Poids total de(s) bobines neuves (g)" avec la colonne "Poids restant".<br>
> Quand le poids restant en grammes atteint 30% de la valeur en grammes initiale de la bobine neuve, la ligne complète change de couleur et le texte "⚠️Filament bientôt épuisé" apparait dans la colonne "Alerte".<br>
> Vous donnant ainsi l'information de penser à remplacer sous peu votre bobine.

<br />

- ### :black_square_button: Macro Annuler la modification<br> 

Grâce à cette macro (bouton) vous pouvez annuler la dernière modification apportée à la colonne **`Poids restant`** par rapport à une valeur entrée dans la colonne **`Nouvelle consommation de filament`**<br>
Cette macro fonctionne à chaque appuie et annule la modification précédente.  

<p align="center">  
<img src="https://github.com/user-attachments/assets/ddbad7d7-3324-48e3-a90c-1d06ba1b6f30"/>
</p>

<br />

> Ex : Si vous renseignez un poids restant de 800g et une nouvelle consommation de filament de 200g alors que vous vouliez renseigner 150g,
> ce bouton (macro) vous permet comme son nom l'indique, d'annuler la dernière modification apportée à la colonne Poids restant par rapport à la valeur renseignée dans Nouvelle consommation de filament.<br>

</details>

<br /><br />

<h2 align="center">:clipboard: Synthèse</h2>

<p align="center">  
  <img src="https://github.com/user-attachments/assets/355bbc84-a4ee-40c6-8540-d1be2d6c8fbd"/>  
</p>

<details>

<summary>Cliquez pour dérouler :arrow_down_small:</summary><br>

La **`Feuille Synthèse inclut une Macro`** qui vous permet de **`regrouper les données`** renseignées dans la **`Feuille Inventaire`** afin d'avoir une **`vision plus claire`** de vos **`filaments, leurs nombres (bobines) et leur quantité`**.
**`Si plusieurs filaments identiques`** sont répartis sur des **`lignes différentes`**, la synthèse permet de **`comptabiliser le poids total des bobines identiques et leurs nombres`**.<br>

<p align="center">  
  <img src="https://github.com/user-attachments/assets/86ebd137-ece7-4b3b-b4f6-e423ffff4253"/>  
</p>

<br />

Si vous **`apportez des modifications à votre inventaire`**, **`cliquez simplement à nouveau sur la macro "Synthétiser l'inventaire"`** pour **`mettre à jour les données`**

</details>

- ## Support me  
<a href="https://ko-fi.com/korsiro"><img src="https://ko-fi.com/img/githubbutton_sm.svg" width="200"></a>

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/korsiro)
