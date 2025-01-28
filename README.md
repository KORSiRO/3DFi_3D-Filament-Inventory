<h1 align="center">3DFi - 3D Filament Inventory</h1>

<p align="center">  
  <img src="https://github.com/user-attachments/assets/7dfce432-5eb8-4d2b-8eec-9790c35aeeca"/>  
</p>

<br />

## ⬇️ Video of how the file works ⬇️<br>

[![Watch the video](https://github.com/user-attachments/assets/29f38d4c-c530-4949-a487-fa41f8b59640)](https://youtu.be/bSyMhTsakyI)

<br />



### :arrow_right: [README en Français](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README_FR.md)

### ⬇️ [Download](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/releases)

<br />

3DFi is an Excel spreadsheet that allows you to track your 3D filament consumption.<br>
Several values are taken into account to allow you to be as accurate as possible.

<br />

> [!NOTE]
>* *This table consists of 16 columns and 2 sheets, each of which has an important role.*

<br />

### TABLE OF CONTENTS:
<details>

<summary>Sheet 1 : Inventory :arrow_down_small:</summary><br>

- :curly_loop: [Spool(s) Quantity](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README.md#curly_loop-spools-quantity-)
- :new: [Total weight of new spool(s) (g)](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/tree/main#new-total-weight-of-new-spools-g-)
- :memo: [Filament Type" and "Filament Brand](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/tree/main#memo-filament-type-and-filament-brand-)
- :art: [Colors](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/tree/main#art-colors-)
- :chart_with_downwards_trend: [Remaining weight (g)](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README_EN.md#chart_with_downwards_trend-remaining-weight-g-)
- :file_folder: [Storage Location](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README_EN.md#file_folder-storage-location-)
- :flower_playing_cards: [TD (Hueforge)](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README_EN.md#flower_playing_cards-td-hueforge-)
- :clock130: [Drying time (mins)](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README_EN.md#clock130-drying-time-mins-)
- :fire: [Nozzle/Plate Temperature](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/tree/main#fire-nozzleplate-temperature)
- :sweat_drops: [Flow](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/tree/main#sweat_drops-flow)
- :bar_chart: [K factor](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/tree/main#bar_chart-k-factor)
- :arrow_heading_down: [New filament consumption (g)](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README_EN.md#arrow_heading_down-nouvelle-consommation-de-filament)
- :warning: [Alert" and "% remaining](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README_EN.md#warning-alert-et--remaining-)
- 🔲 [Cancel modification Macro](https://github.com/KORSiRO/3DFi_3D-Filament-Inventory/blob/main/README_EN.md#black_square_button-macro-annuler-la-modification)

<br />

</details>  

## :clipboard: Sheet 1

<details>

<summary>Click to expand :arrow_down_small:</summary>


- ### :curly_loop: Spool(s) Quantity<br>

Present to indicate the number of identical reels for the same line.

<br />

- ### :new: Total weight of new spool(s) (g)<br>

Present to provide the total weight in grams of the identical spool(s) for the same line.
   
<br>
   
> <ins>Ex:</ins> if you have in your inventory 3 spools of Bambu Lab brand black filament of 1kg each, enter "3000g"

<br />

- ### :memo: Filament Type" and "Filament Brand<br>

<p align="center">  
<img src="https://github.com/user-attachments/assets/39a6704a-9d40-4134-b052-baa9dc709743"/>
</p>  

These 2 columns contain 2 lists: **`"Filament Type"`** and **`"Filament Brand"`**  
The sources for these lists are available in the **`"Materials"`** sheet.  
They already contain more than **`150 pre-recorded data`**.

<br />

<p align="center">  
<img src="https://github.com/user-attachments/assets/9f642785-ef45-4da9-bb6b-6d1ad0d2ab7c"/>
</p>  

These lists can be modified to add one or more filament types/brands.  
Simply add what you want in the corresponding column so that you can then find it in the list of the corresponding column on the **`"Inventory"`** sheet.

<br />

- ### :art: Colors :<br>

  As you will have understood, this column supports the color of the filament. 

<br />


- ### :chart_with_downwards_trend: Remaining weight (g)<br>

This column allows you to obtain the remaining weight of a reel taking into account 2 values:  
- The **`"Total weight of new spool(s) (g)"`**
- The **`"New filament consumption in (g)"`**<br>

<br>

  > <ins>Ex:</ins> If you enter 1 spool of 1000g (new) on the first line and you wish to deduct the quantity of filament used by a print in progress in the column "New filament consumption in (g )",
  > an automatic subtraction is carried out in the "Remaining weight" column to give you the most accurate result possible of the remaining quantity.

<br />

- ### :chart_with_downwards_trend: Storage Location<br>

Makes it easier to find your reels if they are stored in different places in your workshop, office or dedicated room. 

<br />

- ### :flower_playing_cards: TD (Hueforge)<br>

HueForge's TD is a number indicating the amount of light the filament lets through.  
Useful if you often print Hueforge to have this value quickly in front of you depending on the filament used.

<br />

- ### :clock130: Drying Time (mins)<br>

As for "TD (Hueforge)" it is a value that is interesting to have in front of you quickly when you need it.

<br />

- ### :fire: Nozzle/Plate Temperature<br>
  
Do I really need you to explain what this cell is for? :stuck_out_tongue_winking_eye:

<br />

- ### :sweat_drops: Flow<br>

The **`Flow`** corresponds to the volume of filament passing through the extruder.<br>

<br />

- ### :bar_chart: K factor<br>

As a reminder, the K Factor is a value used to determine the maximum printing speed while limiting mechanical vibrations.<br>
In other words, the K Factor makes it possible to adjust the acceleration in the movement of the axes to guarantee a good balance between speed and quality

<br />

- ### :arrow_heading_down: New filament consumption (g)<br>

Briefly mentioned in the previous part, the column **`"New filament consumption in (g)"`** allows you to automatically subtract the filament consumption of a print in progress from the remaining weight of one or more spools.< br>
The last weight that appears in the **`"Remaining weight"`** column is in memory.<br>
If you enter a **`New filament consumption`** the subtraction continues from the last weight in memory.

<br>

> <ins>Ex:</ins> If you enter a remaining weight of for example 800g and a print plans to use 200g of filament,<br>
> by entering the value of 200g in the column **`"New filament consumption in (g)"`** the remaining weight is automatically adjusted (800-200 = 600g remaining).<br>*
> Always to allow you to have precise monitoring of your usage.

<br />

- ### :warning: Alert" et "% remaining<br>

These two columns are a little different from the others.  
They tell you with text and a bright color that your filament is almost exhausted.  
No need to manually enter a value, everything is automated.  

<p align="center">  
<img src="https://github.com/user-attachments/assets/375273c1-49d3-4407-9b73-8b8c07cb00ba"/>
</p>

<br>

> <ins>Ex:</ins> If you enter a total weight of new spools for 1 spool of 1000g and a print in progress consumes 200g of filament, then you enter this value (200g) in the "New consumption" column of filament in (g)".<br>
> As a result, the remaining weight will therefore be 800g and will be automatically entered in the “Remaining weight” column.<br>
> At the same time, the “% remaining” cell gives you this information by comparing the “Total weight of new spool(s) (g)” column with the “Remaining weight” column.<br>
> When the remaining weight in grams reaches 30% of the initial value in grams of the new spool, the complete line changes color and the text "⚠️Filament soon exhausted" appears in the "Alert" column.<br>
> Giving you the information to think about replacing your spool shortly. 

<br />

- ### :black_square_button: Cancel modification Macro<br>

Using this macro (button) you can cancel the last modification made to the **`Remaining weight`** column in relation to a value entered in the **`New filament consumption`** column<br>
This macro works with each press: cancellation of the previous modification.  

<p align="center">  
<img src="https://github.com/user-attachments/assets/363b2807-f869-4251-a2e5-820e2e901deb"/>
</p>

<br>

> <ins>Ex:</ins> If you enter a remaining weight of 800g and a new filament consumption of 200g when you wanted to enter 150g,
> this button (macro) allows you, as its name suggests, to cancel the last modification made to the Remaining weight column compared to the value entered in New filament consumption.<br>

<br />

</details>  

## Support me  
<a href="https://ko-fi.com/korsiro"><img src="https://ko-fi.com/img/githubbutton_sm.svg" width="200"></a>

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/korsiro)
