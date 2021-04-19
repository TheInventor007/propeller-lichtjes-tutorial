# Tutorial

## Step 1
Tijdens deze tutorial gaan we een propeller op het scherm  laten verschijnen. Om te beginnen hebben we enkel de ``||basic:altijd||`` blok nodig. Je kunt een blok verwijderen door deze naar de toolbox links te slepen. 
Je kunt dit nu doen voor de ``||basic:starten||`` blok. 

During this tutorial we will show you how to make a propeller appear on the screen of the micobit. 
For this, we only need the ``||basic:forever||`` block. You can delete a block by dragging the block to the toolbox on the left of your screen. 
You can try this now for the ``||basic:on start||`` block.
## Step 2
Nu kunnen een blok invoegen die led lichtjes laat zien. Deze vindt je in de ``||basic:basis||`` groep. Merk op dat de kleur van ``||basic:toonleds||`` blauw is. Dit geeft ook een indicator in welke groep je een blok moet gaan zoeken.

Now we have to add a block that shows lights. You can find this block in the ``||basic:basis||`` group. Notice the color of the word ``||basic:showLeds||`` is blue. This gives an indication in which group we have to look for the block. 
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
Om een mooie propeller te maken moeten we de lichtjes met de klok mee verplaatsen. We kunnen dit doen door op de led lichtjes te klikken om deze te laten uitgaan en dan op het knopje er naast te klikken met de klok mee.
Bijvoorbeeld naar rechts voor de bovenste 2, naar onder voor de rechter 2 lichtjes, enzovoort...

To make a nice looking propeller, we have to shift the dots clockwise. We can do this by clicking on the button to make the led light go dark and then clicking on the buttons next to it in a clockwise fashion.
For example to the right for the upper 2 lights, down for the right 2 lights and so on...

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
