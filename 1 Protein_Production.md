# Production and purification of BglB

This is a guide to the production and purification of β-glucosidase B from [*Paenibacillus polymxa*](https://en.wikipedia.org/wiki/Paenibacillus_polymyxa) beginning with purified plasmid and ending with purified protein. This protocol and the associated scripts and data in this repository are part of the [Siegel group](https://sites.google.com/site/ucdsiegellab/)'s "Bagel" project. 

For this procedure, typical yields are 1.0 ± 0.4 mg/mL for the wild type protein. 

Before beginning, make sure you have the following ready and standing by:

+ M "sous-vide" water bath set to 42 ˚C
+ 37 ˚C standing, 37 ˚C shaking, and 18 ˚C shaking incubators 
+ Make sure to reserve your spot on the whiteboard and enusre there will be room for you in the shakers for the nights between day 2 and 3
+ Centrifuges for 50 mL Falcon tubes (up to 4,700 RPM) and 2 mL tubes (up to 14,700 RPM) 

## Mise en place

*Mise en place* is a French culinary phrase which means "put in place", as in "set up". It is used in professional kitchens to refer to organizing and arranging the ingredients that a cook will require for the items that are to be prepared during a shift ([Wikipedia](https://en.wikipedia.org/wiki/Mise_en_place)). 

## Day 0: Kunkel mutagenesis 

After we have designed our set of mutants, we mutate the wild type Bagel plasmid to your designed sequence using [Thomas Kunkel's original procedure](http://www.pnas.org/content/82/2/488.full.pdf) or [our group's manual Kunkel protocol](https://docs.google.com/a/ucdavis.edu/folderview?usp=sharing&id=0B3zIXvOOrmpqcEM5WWRadThsVUE). If you're interested, historically orders were carried out on Transcriptic's cloud lab platform (see [Python code that automates the Kunkel procedure and algorithmicly evaluates sequence verification](https://github.com/dacarlin/bagel-orders)). 

## Day 1: Transformation 

In this step, you will transform the plasmids encoding your mutant genes into *Escherichia coli BLR(DE3)*. Transformation is the process of physically shocking the bacteria (heat or electricity depending on the procedure) to induce them to take up foreign DNA from the environment. Today, you will heat shock the *E. coli* to induce the uptake of the plasmid encoding the mutant you designed. 

Material | Concentration  | Amount per reaction
---------|----------------|--------------------
Chemically-competent *Escherichia coli* BL21(DE3) | | 25 μL 
Mutant plasmid solution | > 20 ng/μL | 1 μL
Terrific broth (TB) | | 200 μL
LB agar plates with 50 µg/µL kanamycin | | 1
Sterile glass beads | | 8–10 
15 mL round-bottom culture tube | | 1

### Mise en place

+ Benchtop waste bucket 
+ Rack for 15 mL tubes 
+ Pipettors and tips
+ Ice in ice bucket
+ Pre-warmed "sous-vide" water bath (42 ˚C) 
+ Bunsen burner
+ Striker
+ Agar plates (check that we have pre-made plates before starting the procedure. If there aren't any, ask Ryan, Morgan, or Katie.)

### Instructions 

1. First light Bunsen burner and be sure to work close to the flame to keep contaminants from falling into your samples
  + DO NOT LEAVE BURNER UNATTENDED! ALWAYS TURN IT OFF BEFORE LEAVING THE BENCH FOR ANY AMOUNT OF TIME!
  + Sterility is important for days 1 through 3. Always have a burner and do not expose cultures to open air for extended periods
1. Dispense 1 µL aliquots of your mutant plasmid into the very bottom of the 15 mL round-bottom tubes 
2. Set the round-bottom tubes on ice and incubate on ice for 5 minutes 
3. While the tubes are chilling, get "chemical competent BLR" cells from -80 ˚C freezer and set on ice
4. When the tubes are ice cold and cells are no longer frozen, add competent cells to the 15 mL tubes and incubate on ice for 15 minutes to allow cells to mix with the plasmid (make sure the cell droplet and plasmid droplet are together!)
6. While waiting, set the liquid heat bath "sous-vide" machine to 42 ˚C and press the play button to begin heating the water (the play button will turn white when heating begins)
5. Heat shock at 42 ˚C for 90 seconds 
6. Incubate on ice for 90 seconds 
5. Add 200 µL Terrific Broth and recover with shaking at 37 ˚C for 1 hour 
6. Turn off water bath by pressing the play button again (play button will turn red)
6. Wipe condensation off of outside of plates and label the agarose side of the plates
6. Before the hour is up, add about 5 to 10 glass beads to each plate
6. Pipette 200 µL recovered cells on to plate and shake to spread out the cells
7. After waiting a minute so that the liquid is absorbed, turn the plates upside down so that the beads fall onto the underside of the lid, and deposit beads into bleach solution for later recovery
7. Incubate plate *upside down (agarose half on top)* overnight at 37 ˚C

### Tips and tricks 

+ Chemical competent cells should be kept on ice at all times and never warmed
+ Bring the ice bucket to the freezer to limit time cells are out of freezing temperatures 
+ Some tips for [troubleshooting transformations from New England Biolabs](https://www.neb.com/tools-and-resources/usage-guidelines/chemical-transformation-tips) 
+ If you are getting poor transformation efficiency, try recovering with 400 µL of media for 2 hours at 37 ˚C

## Day 2: Growth 

Today, you will inoculate liquid cultures with one colony from your plates to grow up overnight to increase the number of cells we have to work with for day 3. 

Material | Amount per reaction
---------|---------------------------
Transformation plate from day 1 | 1
Terrific Broth | 5 mL
Kanamycin solution | 5 μL
Tube seal | 1
50 mL Falcon tube | 1 

_Always make enough solutions for the number of samples you have plus 1_

_Minirecipe_ (for 4 samples) : 25 mL induction medium = 25 mL Terrific Broth + 25 µL kanamycin solution

_Minirecipe_ (for 8 samples) : 45 mL induction medium = 45 mL Terrific Broth + 45 µL kanamycin solution

### Mise en place 

+ 50 mL tube rack 
+ Benchtop waste bucket 
+ Pre-cut breathable seals
+ Pipettors and tips 
+ Serological pipette aspirator 
+ 25 mL serological pipette
+ Bunsen burner
+ Striker

### Instructions 

1. Light Bunsen burner within 2 feet of where you will be working
2. Add kanamycin solution to Terrific Broth in an autoclaved flask to make a batch of growth media for all of your mutants. Make enough for one extra culture (n + 1)
3. Aliquot 5 mL growth media to each 50 mL Falcon tube 
1. Using a P2 pipette, use the tip to carefully touch a single colony from the plate and dip in the growth media in the Falcon tube, and pipette up and down a few times to inoculate the culture 
5. Seal the cultures with tube seals (one sheet of breathable seal can be cut into 8 squares for 8 tubes) 
6. Incubate with shaking at 37 ˚C for 24 hours

###Tips and tricks

+ If you have colonies that are white, are not smooth on the surface, and have rough edges they may be contamination. Do not inoculate with one of these colonies; choose a small, round shiny colony. 

## Day 3: Expression cultures 

In this step, you will exchange the spent growth media in your cultures with fresh growth media supplemented with [isopropyl β-D-1-thiogalactopyranoside](https://en.wikipedia.org/wiki/Isopropyl_β-D-1-thiogalactopyranoside) (IPTG). IPTG induces expression of your target protein using the engineered [pET expression system](http://www.genomics.agilent.com/article.jsp%3FpageId%3D472). 

Material                      | Amount per reaction
------------------------------|---
growth cultures from day 2    | 1
Terrific Broth                | 5 mL
1000x IPTG solution           | 5 μL
1000x kanamycin solution      | 5 μL
tube seal                     | 1

_Minirecipe_ (for 1 sample): 5 mL induction medium = 5 mL Terrific Broth + 5 µL kanamycin solution + 5 µL IPTG solution
_Minirecipe_ (for 4 samples) : 25 mL induction medium = 25 mL Terrific Broth + 25 µL kanamycin solution + 25 µL IPTG solution

### *Mise en place*

+ Benchtop waste bucket
+ 25 mL tube rack
+ Vortexer
+ Pipettors and tips
+ Serological pipette asperator
+ 25 mL serological pipette
+ Bunsen burner
+ Striker

### Instructions

1. Centrifuge growth cultures at 4,700 RPM for 10 minutes 
2. Peel the seals off and pour the supernatant from the tube into a flask (does not need to be autoclaved)  
4. Make a batch of induction media (make enough for n+1) 
1. Add 1 mL induction media to cell pellet in tube 
1. Vortex to resuspend pellet
1. Add 4 mL more induction medium to tube
1. Seal with tube seals
1. Incubate with shaking at 18 ˚C for 24 hours 

### Tips and Tricks 

+ The more you observe sterile technique, the better the cultures will grow 

## Day 4: Protein purification 

Today, you will purify the protein you designed for testing using a technique called *immobilized metal ion chromatography*. 

Material | Amount per reaction
---------|-----------------------------
Expression culture from day 3 | 5 mL
Wash buffer | ~ 5 mL 
BugBuster | 50 μL
Dry lysis mix | 1 mg
2 mL tube | 1
Protein buffer | 200 μL
Ni-NTA resin slurry | 100 μL

### Hardware

+ centrifuge 
+ rocker 

### Mise en place 

+ waste bucket 
+ tube rack 
+ flow-through collector
+ microcolumns
+ P1000 and tips 

## Method 

_Minirecipe (for 4 samples make n + 2):_ 2500 uL lysis buffer = 2700 uL wash buffer + 300 uL 10X BugBuster + 6 mg dry lysis mix

_Minirecipe (for 8 samples make n + 2):_ 5000 uL lysis buffer = 4500 uL wash buffer + 500 uL 10X BugBuster + 10 mg dry lysis mix

### Cell lysis and clarification  

1. Centrifuge expression cultures at 4,700 RPM for 10 minutes
2. While they are spinning, make lysis buffer and set on rocker
3. Unseal culture and pour away supernatant 
4. Add 500 uL wash buffer to pellet and vortex to resuspend (should have about 1 mL in there) 
5. Aliquot the resuspended pellets to fresh 2 mL tubes 
1. Aliquot 500 µL lysis buffer into resuspended pellets in 2 mL tubes
1. Rock tubes for 30 minutes at room temperature to lyse cells 
1. Centrifuge at 14,700 RPM for 30 minutes in the large ultracentrifuge to clarify the lysate 

### Purification by immobilized metal ion chromatography 

While centrifuging, prep your microcolums. If necessary, rinse with water. Set cleaned microcolumns in rack over waste collector before you begin purification. 

1. When there are 15 minutes left in the centrifugation cycle, begin washing microcolumns forward and backward with DI water to ensure there is no beads left from the last use
1. Add 100 µL Ni-NTA resin slurry to bed of each microcolumn
1. Add 500 µL wash buffer and allow to drip through
1. Once the lysed cultures have finished spinning, add 500 µL of clarified supernatant and allow to drip through 
1. Add another 500 µL of supernatant and allow to drip through  
1. Wash six times with 500 µL of wash buffer, allow to drip through each time
1. Once the wash buffer has stopped draining out of the tube you need to remove the remaining liquid off of the beads
1. Take a kimwipe and run the bottom of the column along the wipe until the rest of the liquid is sucked out of the column by capillary action.
1. Once all unwanted proteins and wash buffer have been drained, transfer the column to fresh tube
1. Add 150 µL protein buffer directly to beads and incubate at room temperature for 1 minute
1. Flick the tube so that the blue bead bed is disturbed and makes the protein buffer solution cloudy
1. Add a second 150 µL protein buffer and pulse in the centrifuge by holding down the fast forward button for about 3-5 seconds to ensure you get all the liquid
3. Remove the column from the 2 mL tube. This tube contains purified protein solution you worked all week to create!
1. Wash out the columns with DI water 

### Next steps 

1. [Quantitate by absorbance at 280](./gel_and_yields.md)
2. [SDS-PAGE analysis for purity](./gel_and_yields.md) 
3. [Assay for kinetic (Michaelis-Menten) parameters](./kinetic_assay.md) 
4. [Assay for thermal stability (not uploaded)]
5. ALWAYS REMEMBER TO THROW AWAY YOUR 2 mL TUBE OF PROTEIN AND CULTURE PLATE WHEN YOU ARE DONE TAKING MEASUREMENTS AND ASSAYING! KEEP THE 4˚C COLD ROOM CLEAR!
