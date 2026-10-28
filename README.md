# Sequential-gearbox
This is my custom sequential gearbox project. I built it for week 2 of Hack Club Half Life, as a CAD project. I designed this whole project in fusion 360. I am a big fan of motorsports, and I thought that a gearbox like this is a really interesting project, having a lot of interesting mechanisms in it.

## What is a sequential gearbox?  
A sequential gearbox is a type of gearbox that allows super fast shifting, and doesn't require a clutch to operate, only at starting. Because of it's fast shifting, lower size & weight, it is mainly used in motorcycles and racecars. One of the main things different about this compared to a more traditional H pattern gearbox, is that it doesn't let you skip gears, you can only shift up or down sequentially, hence the name sequential gearbox.

## My model 
My design is a custom open layout 4 gear(+ neutral) gearbox. It doesn't have a gear selector lever like most similar gearboxes, only a knob that you can select gears with by rotating. This is meant to be a demonstration model, so it is not designed to handle larger loads, only meant to be driven by either a small electric motor, or the crank that is included in the files, and is also not really efficent because of the nearly fully 3D printed construction.

## Printing
To print, you will either have to print all the parts in the Gearbox_PLATE.stl file, and slice them in your preferred software, or with a Bambu Lab printer you can just open the Gearbox_PLATE.3mf file, and have all the slicer settings already set(Note that you might need to make some modifications if you aren't using an A1 min and PETG Basic). The slicer file has been done for the A1 mini, with Bambu PETG Basic, since that is the printer/filament that I use. The settings have been tested with test prints of some parts, so that's why I use these. The main settings are from the Bambu Lab 20mm preset with the 4 mm nozzle, I just worked on the supports, and the infil.

## Assembly
1. First you will  need to take the right side, and insert the shafts into teir respective holes
2. After that, you should slide the gears onto  the bottom shaft(layshaft), from smallest to largest. At this point you don't need to worry about spacing.
3. After you're done with that, you should screw on the bottom panel to the side, here, the stabilizers will help you make sure that the spacing is right.
4. Next you can move onto the output shaft. It should be simple, just push it through the hole, it has the gear printed on
5. After that you should slide the other side on, to all the shafts you have now, and also add the input shaft.
6. Add the gears onto the input shaft, making sure that the dog clutches orientation is correct, and also between the gears you should add the 2 dog clutch engagment pieces.
7. Next you should fix the middle stabilizer between the layshaft and the input shaft, and also add the stabilizer on top of the rings. Also add the dog clutch activator arm, and it's satbilizor connecting it to the shifting shaft.
8. Screw both sides together, with the help of the long spacer rods, and also the stabilizer in the middel and towards the top on the dog clutch activator arms stabilizer.
9. Lastly you should add the gear selector wheel, and the crank to finish off the project

If at any point you get stuck with the assembly, use the  assembled CAD model for reference.  
(Note that this project has not yet been built, and there is a possibility that not everything will fit together perfectly, if that is the case, I'll update this repo)

## Images 
Full construction:  
![CAD model](https://github.com/jivespark/Sequential-gearbox/blob/main/Images/Assembly.png?raw=true)

Plate:  
![Printable plate](https://github.com/jivespark/Sequential-gearbox/blob/main/Images/Plate.png?raw=true)

## BOM
| Item                     | Qty | Supplier   | Cost/item | Total Cost | link                                                                    |
|--------------------------|-----|------------|-----------|------------|-------------------------------------------------------------------------|
| M3x10 screws             | 1   | Aliexpress | $2.43     | $2.43      | https://www.aliexpress.com/item/4000117933430.html                      |
| Filament                 | 1   | Bambu lab  | $13.99    | $13.99     | https://us.store.bambulab.com/products/petg-basic |
| Estimated total shipping | 1   |            |           | $0.00      |                                                                         |
