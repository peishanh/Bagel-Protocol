# Kunkel Mutagenesis

#### Design mutagenic oligo using statagene’s primer design and order the 5’-&gt;3’ antisense oligo
1. This is specific for pET29b+, other vectors may require the sense oligo
2. If you are using multiple oligos for several changes at once, make sure they do not overlap. You may need to make a longer/shorter oligo to encode all the mutations on one oligo (but this is expensive after 100bp) or break it into several oligos with shorter compliments.
#### Kinase oligo in a 96 well plate
1. Make Kinase Reaction Mix (make #rxn+2)
  * 3uL PNK Buffer/rxn
  * 1uL of 10mM ATP/rxn
  * 1uL T4 Polynucleotide Kinase/rxn
  * 18uL ddiH2O/rxn
2. Combine oligo and reaction mix in PCR strip tubes or 96well PCR Plate
  * Aliquot 23uL of Kinase Reaction Mix using repeater
  * Make sure all liquid at the bottom by tapping or briefly spinning
  * Add 7uL of 100uM oligo to the BOTTOM of each well and pipette up and down
3. Seal, MIX gently by tapping, and incubate at 37deg C (metal bath or PCR machine) for 1 hour
4. Store on ice short term, or -20 long term
  * These can be re-used in the future so no need to throw them away!

#### Dilute Mutagenic Kinased Oligo (Optimal molar ratio is 1:4 dU-ssDNA:Oligo)
1. Add 2uL of oligo into 200uL of diH20 and then MIX WELL!
  * If doing a mutant with multiple oligos add 2uL of EACH oligo to the same tube
  * This dilution factor will achieve the desired 1:4 dU-ssDNA:Oligo molar ratio for most single stranded DNA preps.
  
#### Anneal Diluted Oligo and ssDNA
1. Combine 0.2uL of T4 DNA Ligase Buffer with 2uL of ssDNA, (make #rxn+2)
2. Aliquot 2.2uL of the mix into a in a fresh PCR plate or strip tubes
3. Make sure all the liquid as the bottom by spinning down or tapping
4. Add 2uL of THE DILUTED kinased primer (single or mixed) to generate desired mutant to the bottom of the plate and PIPPETE UP AND DOWN TO MIX.
  * Always do a background as well where you have ssDNA with NO oligo (just add 2uL of water). This will allow to you to know if you mutations work and estimate your mutation efficiency so you can pick the appropriate number of colonies you need to screen in order to find the mutation desired.

5. Seal, MIX (tapping or plate mixer)
6. Anneal Oligo to DNA (USE heated lid)
  * Slow Anneal in a PCR machine: Start at 95 degrees and ramp down to 25 over an hour (use ANNEALIN or )

#### Polymerize DNA
a. Make polymerization reaction mixture (make #rxn+2)
i. 0.6uL 10x T4 Ligase Buffer/rxn
ii. 0.4uL 25mM dNTPs/rxn
iii. 0.4uL 10mM ATP/rxn
iv. 0.4uL T7 Polymerase (unmodified from NEB)/rxn
v. 0.4uL T4 Ligase/rxn
b. Add 2.2uL of polymerization reaction mixture to each annealing reaction
c. Seal, mix (tapping or plate mixer)
d. Incubate at room temperature for 1+ hrs.
7. Transform (electroporation is more reliable for kunkels than chem comp, but if high efficiency chem
comp cells should work as well)
a. Dialyze DNA (ORDER IS IMPORTANT HERE!!!!)
i. Add ~40mL of diH2O to an empty Petri dish (till it is mostly full)
ii. Mark up to 8 spots on the shiny side of a 0.025um membrane filter
iii. Place the filter into the diH2O so shiny side is up and it is flat
1. DO NOT SUBMERGE!
iv. CAREFULLY pipette the 5uL reaction onto the designated spots
v. Let dialyze for 20+ minutes
b. Electroporate
i. CAREFULLY remove the reaction and pipette into the bottom of the crevice in the
0.1cm electroporation cuvettes and KEEP ON ICE
ii. Add 30uL of electro competent BL21(DE3)* cells (Competent Cell Rack, Box labeled
“BL21*-ELECTROCOMP”, tubes labeled E*)
iii. Place into BioRad electroporater (only fit in 1 way) set to Bacteria and hit
“Pulse”
iv. IMMEDIATLEY add 200uL of media (TB or LB, NO antibiotic) into the
cuvette to extract cells, transfer to a fresh strip tube or PCR plate.

c. Recover and Plate
i. Incubate 37deg for ~1hr
ii. On individual plates (not sure how to get around this) plate out ~200uL of each
reaction

1. I find it works best to do 12 plates at a time
a. Add ~10 glass beads/plate
b. Add the 200uL of solution
c. Shake to spread
d. Turn plate and tap so beads are transferred to the lid, than pour
out beads into 70% EtOH filled beaker.
e. Move to the next row.
iii. Dry plates at 37deg for ½ hr, lid-side up.
iv. Turn plates so agar side is up and incubate at 37deg overnight

