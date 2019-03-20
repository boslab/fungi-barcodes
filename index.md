---
title: Fungi DNA barcoding and phylogenetic analysis
author: Peter J. Collins
date: 2018-08-23
bibliography: biblio.yaml
keywords: [bioinformatics, gene library, phylogenetic DNA barcodes]
abstract: |
 @todo
---

# Introduction

@todo


# Materials and methods

@todo

## Generating biomass for DNA extraction

I prepared 35 mL MYPB in a 50 mL Falcon tube for each sample (malt--yeast--peptone broth; 20 g/L malt extract and 1 g/L each yeast extract and peptone).
Then I fermented them for 14 days in a New Brunswick Innova 4000 Incubator Shaker ("shake 'n bake"; 250 RPM and 25 °C).
Discrete 3D colonies formed as the samples shook and book.

I centrifuged the Falcon tubes for 20 min at 4,000 RPM and 25 °C in an Eppendorf 5810 R.
Then I collected 1.5 mL samples of the broth and metabolites for possible further analysis.
Mass spectrometry and thin-layer chromatography are two options, depending on equipment availability.

I poured off the remaining broth and stuffed the mycelium into 2 mL centrifuge tubes with an inoculation loop.
Then I centrifuged them for 10 min at 14,000 RPM in an Eppendorf 5415 C.

I pippetted out the supernatant, filled each tube with 750 μL normal saline (0.9% NaCl), vortexed them for 5s, then centrifuged them again.
I repeated this step 3×, vortexing and centrifuging until the samples were reasonably free of broth.

I transferred the washed pellets to fresh tubes and centrifuged them once more without added saline.
This removed any remaining liquid and helped prepare them for storage at --20 °C until I could perform the DNA extraction.
I weighed each pellet before freezing it, subtracting the 1.20g that an empty tube weighs.

The total biomass of each sample ranged from 360--1,360 mg ± 10 mg.


## Extracting DNA from the mycelium pellets

I extracted the DNA from 250 mg frozen mycelium samples using a NucleoSpin Soil purification kit (Machery-Nagel GmbH, Düren, Germany; reference #740780.50).
I used lysis buffer SL1 without the enhancer SX and followed [the BosLab protocol annotations](BosLab.v2.protocol.pdf).
I used 65 μL DNA elution buffer, the middle of the recommended 30--100 μL range.

## Doing PCR on the DNA extract

| Phase			| Time (s)	| Temperature (°C)	| Cycles	|
| ---			| ---		| ---			| ---		|
| Denaturation I	| 120		| 95			| 1		|
| Denaturation II	| 30		| 95			| 30		|
| Annealing		| 30		| 54			| 30		|
| Extension		| 55		| 72			| 30		|
| Cooling		| ∞		| 4			| nil		|

The positive control was a pGreen plasmid [@hellens2000] and the negative control was nuclease-free water.
I ran gel electrophoresis on a miniPCR blueGel system with a 1 kb ladder.
I also ran a Qubit fluorometer with [ADD PARAMETERS].

@todo:
Run the PCR and Qubit again, then send samples for Sanger sequencing.


# Results and discussion

@todo


## 1st generation results

| Species			| P Value	| Date (Y-m-d)	| Biomass (mg)	| Yield (ng/mL)	|
| ---				| ---		| ---		| ---		| ---		|
| *A. aegerita*			| P-5		| 2018-04-10	| 470		| nil		|
| *A. niger* "Carolina"		| P-1		| 2019-02-21	| 650		| nil		|
| *C. comatus*			| P-1		| 2019-03-07	| nil		| nil		|
| *G. curtisii*			| P-1		| 2019-03-07	| nil		| nil		|
| *G. lucidum*			| P-1		| 2018-02-10	| 490		| nil		|
| *G. sessile* "HW"		| P-1		| 2018-02-03	| 420		| nil		|
| *G. frondosa* "Charles River" | P-2		| 2018-12-29	| 420		| nil		|
| *G. frondosa* "Fat Moon"	| P-1		| 2018-02-10	| 840		| nil		|
| *H. abietis*			| P-4		| 2018-02-10	| 360		| nil		|
| *H. coralloides* "Cummington"	| P-2		| 2018-02-10	| 970		| nil		|
| *I. obliquus* "Wild"		| P-1		| 2018-02-10	| 770		| nil		|
| *I. resinosum* "Cummington"	| P-1		| 2018-02-10	| 890		| nil		|
| *L. edodes* "3782"		| P-4		| 2018-02-10	| 720		| nil		|
| *M. scorodonius*		| P-		| 2018-x-y	| nil		| nil		|
| *P. roqueforti*		| P-2		| 2018-02-10	| 750		| nil		|
| *P. nameko* "JPN"		| P-1		| 2018-02-03	| 730		| nil		|
| *P. nameko* "Mycoterra"	| P-7		| 2018-11-20	| 600		| nil		|
| *P. columbinus* "Mycoterra"	| P-5		| 2018-11-20	| 740		| nil		|
| *P. erygnii*			| P-1		| 2019-02-26	| 860		| nil		|
| *P. ostreatus* "Mycoterra"	| P-5		| 2018-11-20	| 1,360		| nil		|
| *P. pulmonaris*		| P-		| 2018-x-y	| nil		| nil		|
| *P. tuber-regium*		| P-2		| 2018-02-10	| 1,100		| nil		|


## Fine-tuning the medium

@todo


# Future work

Anthropogenic mass extinction fundamentally changes the environment and accelerates the rate of random mutations.
Therefore it's necessary to guarantee the persistence and integrity of as many beneficial genomes as possible.


## Reconstructing helpful biomolecules

@todo
