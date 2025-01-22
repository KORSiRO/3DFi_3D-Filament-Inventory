<h1 align="center">3DFi - 3D Filament Inventory</h1>

<p align="center">  
  <img src="https://github.com/user-attachments/assets/31af8efe-ef62-400f-9212-5ce13b734101"/>  
</p>

<br />

### ⬇️ [Download Beta](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/releases)

<br /> 

3DFi is an Excel table allowing you to track your 3D filament consumption.  
Several values ​​are taken into account to allow you to be as precise as possible. 

<br />

> [!NOTE]
>* *This table is made up of 12 columns and 2 sheets which each have an important role.*

 <img src="https://github.com/user-attachments/assets/00fee29d-f7b0-4838-9b5b-6ab21d8734ef"/> 

<br /><br />

### TABLE DES MATIÈRES:
- :curly_loop: ["Quantity of spool(s)"](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README.md#curly_loop-quantit%C3%A9-de-bobines-)
- :new: ["Total weight of new spool(s) (g)"](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#new-poids-total-des-bobines-neuves-g-)
- :memo: ["Filament Type" and "Filament Brand"](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#memo-type-de-filament-et-marque-de-filament-)
- :art: ["Colors"](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#art-couleurs-)
- :chart_with_downwards_trend: ["Remaining weight"](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#chart_with_downwards_trend-poids-restant-)
- :file_folder: ["Storage location"](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#file_folder-lieu-de-stockage-)
- :flower_playing_cards: ["TD (Hueforge)"](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#flower_playing_cards-td-hueforge-)
- :clock130: ["Drying time (mins)"](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#flower_playing_cards-td-hueforge-)
- :warning: ["Alert" and "% remaining"](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/edit/main/README.md#warning-alerte-et--restant-)
- :arrow_heading_down: ["New filament consumption"](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README.md#arrow_heading_down-nouvelle-consommation-de-filament)

<br />

## :clipboard: TABLE FEATURES

<br />

### :curly_loop: "Quantity of spool(s)" :

   Simply enter the number of identical reels for the same line.

<br />

### :new: "Total weight of new spool(s) (g)" :

   Present to provide the total weight in grams of the identical spool(s) for the same line.
   > <ins>Ex:</ins> if you have in your inventory 3 spools of Bambu Lab brand black filament of 1kg each, enter "3000g"

<br />   

### :memo: "Filament Type" and "Filament Brand" :

<p align="center">  
<img src="https://github.com/user-attachments/assets/399afa3a-1b1d-4af3-8b2e-de2667a24441"/>
</p>  

These 2 columns contain 2 lists: **`"Filament Type"`** and **`"Filament Brand"`**  
The sources for these lists are available in the **`"Materials"`** sheet.  
They already contain more than **`150 pre-recorded data`**.

<br />

<p align="center">  
<img src="https://github.com/user-attachments/assets/adbec5de-0775-45d9-8917-beb034a8c579"/>
</p>  

These lists can be modified to add one or more filament types/brands.  
Simply add what you want in the corresponding column so that you can then find it in the list of the corresponding column on the **`"Inventory"`** sheet.

<br />

### :art: "Colors" :

As you will have understood, this column supports the color of the filament.

<br />

### :chart_with_downwards_trend: <ins>"Remaining weight" :</ins>

This column allows you to obtain the remaining weight of a reel taking into account 2 values:  
- The **`"Total weight of new spool(s) (g)"`**
- The **`"New filament consumption in (g)"`**<br>

<br />

> <ins>Ex:</ins> If you enter 1 spool of 1000g (new) on the first line and you wish to deduct the quantity of filament used by a print in progress in the column "New filament consumption in (g )",
> an automatic subtraction is carried out in the "Remaining weight" column to give you the most accurate result possible of the remaining quantity.
<br />

### :file_folder: <ins>"Storage location" :</ins> 

Makes it easier to find your reels if they are stored in different places in your workshop, office or dedicated room.  

<br />

### :flower_playing_cards: <ins>"TD (Hueforge)" :</ins>

HueForge's TD or Transmission Distance is a number indicating the amount of light the filament lets through.<br>  
Useful if you often print Hueforge to have this value quickly in front of you depending on the filament used.

<br />

### :clock130: <ins>"Drying time (mins)" :</ins>

As for "TD (Hueforge) it is a value that is interesting to have in front of you quickly when you need it.

<br />

### :warning: <ins>"Alert" and "% remaining" :</ins> 

These two columns are a little different from the others.<br>  
They tell you with text and a bright color that your filament is almost exhausted.<br>  
No need to manually enter a value, everything is automated.

<p align="center">  
<img src="https://github.com/user-attachments/assets/1b905135-9b02-408d-80f2-acd02d426dd2"/>
</p>

<br />

> <ins>Ex:</ins> If you enter a total weight of new spools for 1 spool of 1000g and a print in progress consumes 200g of filament, then you enter this value (200g) in the "New consumption" column of filament in (g)".<br>
> As a result, the remaining weight will therefore be 800g and will be automatically entered in the “Remaining weight” column.<br>
> At the same time, the “% remaining” cell gives you this information by comparing the “Total weight of new spool(s) (g)” column with the “Remaining weight” column.<br>
> When the remaining weight in grams reaches 30% of the initial value in grams of the new spool, the complete line changes color and the text "⚠️Filament soon exhausted" appears in the "Alert" column.<br>
> Giving you the information to think about replacing your coil shortly.
<br />

### :arrow_heading_down: <ins>"New filament consumption"</ins>  

Briefly mentioned in the previous part, the column **`"New filament consumption in (g)"`** allows you to automatically subtract the filament consumption of a print in progress from the remaining weight of one or more spools.<br>
<br />

> <ins>Ex:</ins> When you enter a remaining weight of for example 800g and a print plans to use 200g of filament,<br>
> by entering the value of 200g in the column **`"New filament consumption in (g)"`** the remaining weight is automatically adjusted (800-200 = 600g remaining).<br>
> Always to allow you to have precise monitoring of your usage.

<br />

## Support me  
<a href="https://ko-fi.com/korsiro"><img src="https://ko-fi.com/img/githubbutton_sm.svg" width="200"></a>

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/korsiro)
