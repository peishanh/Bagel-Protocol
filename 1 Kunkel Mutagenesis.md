# Kunkel Mutagenesis

#### Design mutagenic oligo using statagene’s primer design and order the 5’-&gt;3’ antisense oligo
1. This is specific for pET29b+, other vectors may require the sense oligo
2. If you are using multiple oligos for several changes at once, make sure they do not overlap. You may need to make a longer/shorter oligo to encode all the mutations on one oligo (but this is expensive after 100bp) or break it into several oligos with shorter compliments.
#### Kinase oligo in a PCR tubes
1. Make Kinase Reaction Mix (make #rxn+2) in a PCR tube
  * 3uL PNK Buffer/rxn
  * 1uL of 10mM ATP/rxn
  * 1uL T4 Polynucleotide Kinase/rxn
  * 18uL Nuclease-free water/rxn
2. Combine oligo and reaction mix in PCR strip tubes
  * Aliquot 23uL of Kinase Reaction Mix onto each of your PCR tubes.
  * Make sure all liquid at the bottom by tapping or briefly spinning
  * Add 7uL of 100uM oligo to the BOTTOM of each well and pipette up and down
3. Seal, MIX gently by tapping, and incubate at 37deg C (metal bath or PCR machine) for 1 hour
4. Store on ice short term, or -20 long term (Label with intials and product names)
  * These can be re-used in the future so no need to throw them away!

#### Dilute Mutagenic Kinased Oligo (Optimal molar ratio is 1:4 dU-ssDNA:Oligo)
1. In a PCR tube add 2uL of oligo into 200uL of nuclease-free water and then MIX WELL!
  * If doing a mutant with multiple oligos add 2uL of EACH oligo to the same tube
  * This dilution factor will achieve the desired 1:4 dU-ssDNA:Oligo molar ratio for most single stranded DNA preps.
  
#### Anneal Diluted Oligo and ssDNA (Your samples + background)
1. Combine 0.2uL of T4 DNA Ligase Buffer with 2uL of ssDNA, (make #rxn+1)
2. Aliquot 2.2uL of the mix into a in a fresh PCR plate or strip tubes
3. Make sure all the liquid as the bottom by spinning down or tapping
4. Add 2uL of THE DILUTED kinased oligo (single or mixed) to generate desired mutant to the bottom of the plate and PIPPETE UP AND DOWN TO MIX.
  * Always do a background as well where you have ssDNA with NO oligo (just add 2uL of water). This will allow to you to know if you mutations work and estimate your mutation efficiency so you can pick the appropriate number of colonies you need to screen in order to find the mutation desired.
5. Seal, MIX (tapping or plate mixer)
6. Anneal Oligo to DNA (USE heated lid)
  * Slow Anneal in a PCR machine: Start at 95 degrees and ramp down to 25 over an hour (use ANNEALIN in Bagel Protocol)

#### Polymerize DNA
1. Make polymerization reaction mixture (make #rxn+2)
  * 0.6uL 10x T4 Ligase Buffer/rxn
  * 0.4uL 25mM dNTPs/rxn 
  * 0.4uL 10mM ATP/rxn
  * 0.4uL T7 Polymerase (unmodified from NEB)/rxn
  * 0.4uL T4 Ligase/rxn
  * Note: dNTPs, ATP, and T4 ligase buffer are single USE that's kept in a capsule form in the -20 C
2. Add 2.2uL of polymerization reaction mixture to each annealing reaction
3. Seal, mix (tapping or plate mixer)
4. Incubate at room temperature for 1+ hrs (Not overnight).
5. Transform (electroporation is more reliable for kunkels than chem comp, but if high efficiency chem comp cells should work as well)
6. Store Kunkel products at -20 long term
