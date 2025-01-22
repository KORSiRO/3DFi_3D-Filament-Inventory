<h1 align* "center"*3DFi - 3D Filament Inventory/h1

<p aligned. "center"
<img src'https:/github.com/user-attachments/assets/31af8efe-ef62-400f-9212-5ce13b
</

<

### :[README in English] (https:/github.com/KORSiRO/3DFi-3D-Filament-Inventory/blobden/mainl

### - [Beta version download](https:/github.com/KORSiRO/3DFi-3D-Filament-Inventory/releases)

<

3DFi is an Excel table that allows you to track your 3D filament consumption.
Several values are taken into account to allow you to be as specific as possible.

<

> [!NOTE]
>* *This table is composed of 12 columns and 2 sheets, each of which has an important role. * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *

<ig src'https:/github.com/user-attachments/assets/00fee29d-f7b0-4821-9b5ef

<brown / rb /*

### TABLE OF CONTENTS:
- :curlyo-loop: [quantity-de-bobine(s)](https:/github.com/korsiro/3dfi-filament
- :new: [Total weight of new coils (g)](https:/github.com/KORSiRO/3DFi-Filament-Inventoryines)
- :memo: [Type of Filament" and "Mark of filament] (https:/github.com/KORSiRO/3DFi-Filament-Inventory/editmo
- :article: [couleurs] (https:/github.com/korsiro/3dfi-3d-filament-inventory/edit/main/reoule
- :chartwithin-downwards-trend: [most weight](https:/github.com/korsiro/3dfi-filament-in
- :folder: [Place of storage](https:/github.com/KORSiRO/3DFi-3D-Filament-Inventory/dit/main/READlile
- :flower andplaying-cards: [td (hueforge)](https:/github.com/korsiro/3dfi)
- :(https:/github.com/KORSiRO/3DFi-3D-Filament-Inventory/editome.
- :(https:/github.com/KORSiRO/3DFi-3D-Filament-Inventory/edit/main/REwres)
- :arrow-heading-down: [New filament consumption](https:/github.com/KORSiRO/3DFi-Filament-Inventory/blobd

<

## :Chepboard: CARACTERISTICS OF THE TABLE

<

### :curlyoloop: Quantity of coil(s):

Present to inform the number of identical coils for the same line.

<

### :new: Total weight of new coils (g):

Present to inform the total weight in grams of the identical coil(s) for the same line.
> <If you have in your inventory 3 Bambu Lab black filament coils of 1 kg each, enter "3000g"

<

### :memo: Type of Filament and "S filament mark:

<p aligned. "center"
<img src'https:/github.com/user-attachments/assets/399afa3a-1b1d-4af3-8b2
</

These two columns contain 2 lists: ***"Type of Filament"*** and ***"Mark of Filament"**
The sources of these lists are available on the sheet *** "Materials"**
They already contain more than ***150 pre-recorded data.

<

<p aligned. "center"
<img src'https:/github.com/user-attachments/assets/adbec5de-0775-45d9-8917-beb0
</

These lists may be amended to add one or more filament types/markets.
It is sufficient to add in the corresponding column what you would like to see in the list of the corresponding column on the "Inventory" sheet.


<

### :art:

This column, you understand, ensures that the colour of the filament is taken into account.

<

### :chart: ’insoids remaining:*/ins.

This column gives the remaining weight of a coil with 2 values:
- ***"Total weight of new coils (g)"**
- **"New filament consumption in (g)"**

> <If you are referring to the first line 1 1000g coil (new) and wish to deduct the amount of filament used by a current printing column (New consumption)
> An automatic subtraction is carried out in the "Poids remaining" column to give you the most accurate result of the remaining quantity.

<

### :folder: storage area:*/ins.

Make it easier to search your coils if they are stored at different locations in your workshop, office or room.

<

### :flower/playing-cards: ’insoTD (Hueforge):

HueForge's TD or Transmission Distance is a number indicating the amount of light that the filament leaves.
Useful if you often print Hueforge to have this value quickly below the eyes as a function of the filament used.

<

### :clock130: drying places (rails):

As with "TD (Hueforge) it is an interesting value to have in the eyes quickly when you need it.

<

### :’ins-Alerte" and "per cent remaining:*/ins.

These two columns are somewhat different from the others.
They tell you by a sharp text and colour that your filament is soon exhausted.
No need to manually capture a value, everything is automated.

<p aligned. "center"
<ig src'https:/github.com/user-attachments/assets/1b905135-9b02-408d-80f2-d02
</

> <If you have a total weight of new coils for 1 1000g coil and a current impression is 200g filament, then you will find this value in the new column.
> As a result, the remaining weight will be 800g and will automatically be reported in the "Most weight" column.
> In parallel, the "% remaining" cell gives you this information by comparing the column "Total weight of new coils (g)" with the column "Poids remaining".
> When the weight remaining in grams was 30% of the initial grams value of the new coil, the full line changed colour and the text "Filament soon exhausted" appeared in the "Gross" column.
> This gives you the information to consider replacing your coil shortly.
<

### :arrowheading-down: New use of filament(s)

Issued quickly in the previous part, column **-"New filament consumption in (g)"*** automatically removes a filament consumption from an in-progress impression at the remaining weight of one or more coils.
The last weight shown in column ***"Weights remaining"*** is in memory.
If you are reporting a new filament consumption** the subtraction therefore continues from the last memory weight.

> <If you have a remaining weight of 800g, for example, and an impression is to use 200g of the filament.
> by capturing the value of 200g in column ** New filament consumption in (g)"** the remaining weight is automatically adjusted (800-200 to 600g remaining).
> Also to allow you to have a clear follow-up of your use.
>
<brown / rb /*

### :Black-square-button: ”Macro "Cancel change"*/ins.

Thanks to this macro (button) you can cancel the last change in column **-Weights remaining** compared to a value entered in column ** New filament consumption**
This macro works at every support: annulment of the previous amendment.

<p aligned. "center"
<ig src'https:/github.com/user-attachments/assets/dbad7d7-3324-48e3-a906
</

> <If you have a remaining weight of 800g and a new 200g filament consumption, you would like to inform 150g,
> This button (macro) allows you, as its name indicates, to cancel the last change in the Weights column relative to the value reported in New Filament Consumption.

## Support me
<a href*"https:/Ky-fi.com/korsiro" ”i-zhttps:/ko-fi.com/img/githubbutton

[![Paypal](https://img.shields.io/badge/paypal-00457c? style-for-the-badge-logo-paypalo-logocolor-white)](https:/paypal.me/korsiro)
