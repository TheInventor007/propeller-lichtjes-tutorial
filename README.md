# My Tutorial

## Step 1
Tijdens deze tutorial gaan we een propeller op het scherm  laten verschijnen. Om te beginnen hebben we enkel de 'forever' blok nodig. Je kunt een blok verwijderen door deze naar de toolbox links te slepen. 
Je kunt dit nu doen voor de 'on start' blok.

During this tutorial we will show you how to make a propeller appear on the screen of the micobit. 
For this, we only need the 'forever' block. You can delete a block by dragging the block to the toolbox on the left of your screen. 
You can try this now for the 'on start' block.
## Step 2
Nu kunnen een blok invoegen die led lichtjes laat zien. Deze vindt je in de 'basic' groep. Merk op dat de kleur van 'basic' blauw is. Dit geeft ook een indicator in welke groep je een blok moet gaan zoeken.

Now we have to add a block that shows lights. You can find this block in the 'basic' group. Notice the color of the word 'basic'is blue. This gives the indication we have to look in the blue 'basic' group. 
```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
})
```
## Step 3
Laat nu een lichtje branden door het middelste knopje aan te klikken. Je kunt het lichtje laten stoppen met branden door deze opnieuw aan te klikken.

You can make a dot light up by clicking the middle button on the 'show leds' block. You can make it stop by clicking the button again. 
```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . # . .
        . . . . .
        . . . . .
        `)
})
```
## Step  4 
We kunnen nu een kruis maken door op de 2 led lichtjes boven, onder, links en rechts van het middelpunt te klikken.

We can now make a cross by clicking on 2 led lights above, under, left and right from the middle point.
```blocks
basic.forever(function () {
    basic.showLeds(`
        . . # . .
        . . # . .
        # # # # #
        . . # . .
        . . # . .
        `)
})
```

## Step 5
To make a nice looking propeller, we have to shift the dots clockwise. We can do this by clicking on the button to make the led light go dark and then clicking on the buttons next to it in a clockwise fashion.

Om een mooie propeller te maken moeten we de lichtjes met de klok mee verplaatsen. We kunnen dit doen door op de led lichtjes te klikken om deze te laten uitgaan en dan op het knopje er naast te klikken met de klok mee.
```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . # .
        # # . # .
        . . # . .
        . # . # #
        . # . . .
        `)
})
```

## Step 5
Well done! If you want a more challenging coding excercise about the propeller, be sure to try out our other tutorial.

Goed gedaan! Als je een iets uitdagendere codeer oefening wilt over de propeller kun je onze andere tutorial uitproberen.


> Open this page at [https://theinventor007.github.io/propeller-lichtjes-tutorial/](https://theinventor007.github.io/propeller-lichtjes-tutorial/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/theinventor007/propeller-lichtjes-tutorial** and import

## Edit this project ![Build status badge](https://github.com/theinventor007/propeller-lichtjes-tutorial/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/theinventor007/propeller-lichtjes-tutorial** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/theinventor007/propeller-lichtjes-tutorial/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
