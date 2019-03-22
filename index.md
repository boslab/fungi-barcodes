---
title: Fungi DNA barcoding and phylogenetic analysis
author: Peter J. Collins
date: 2019-03-21
bibliography: biblio.yaml
keywords: [bioinformatics, gene library, phylogenetic DNA barcodes]
abstract: |
 @todo
---

# Introduction

@todo


# Materials and methods

The malt extract came from Boston Homebrew Supply in Brookline, MA.
The yeast extract and peptone came from [add supplier] in [add city].
The DNA extract kit (reference #740780.50) came from Machery-Nagel GmbH in Düren, Germany.

The primers came from Integrated DNA Technologies in Coralville, IA.
Massachusetts General Hospital did the Sanger sequencing.


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

I extracted the DNA from 0.33--0.5g frozen mycelium samples using a NucleoSpin Soil purification kit.
I used lysis buffer SL1 without the enhancer SX and generally followed [the BosLab protocol annotations](BosLab.v2.protocol.pdf).
Note that I performed the SW2 wash twice as in the original protocol and incubated the final elution at 37 °C for 5 min.
I used 50 μL elution buffer, the recommended quantity for a medium-concentration extract.


## Doing PCR on the DNA extract

| Phase			| Time (s)	| Temperature (°C)	| Cycles	|
| ---			| ---		| ---			| ---		|
| Denaturation I	| 120		| 95			| 1		|
| Denaturation II	| 30		| 95			| 30		|
| Annealing		| 30		| 54			| 30		|
| Extension		| 55		| 72			| 30		|
| Cooling		| ∞		| 4			| nil		|

The positive control was a pGreen plasmid [@hellens2000] and the negative control was nuclease-free water.
I also ran a Qubit v1.27 fluorometer assay with 1 μL sample sizes and recalibrated the device each time I used it.

The primer sequences are ITS 1F and ITS4 from [the Fungal Barcoding website developed by NIH/NLM/NCBI](http://www.fungalbarcoding.org/DefaultInfo.aspx?Page=Primers).

@todo:
Run the PCR and Qubit again, then send samples for Sanger sequencing.


# Results and discussion

@todo


## Tabulated yields

| Species			| P Value	| Date (Y-m-d)	| Biomass (mg)	| Yield (μg/mL)	| PCR (μg/mL)	|
| ---				| ---		| ---		| ---		| ---		| ---		|
| *A. aegerita*			| P-5		| 2018-04-10	| 470		| 41.3		| nil		|
| *A. niger* "Carolina"		| P-1		| 2019-02-21	| 650		| nil		| nil		|
| *C. comatus*			| P-1		| 2019-03-07	| nil		| nil		| nil		|
| *G. curtisii*			| P-1		| 2019-03-07	| nil		| nil		| nil		|
| *G. lucidum*			| P-1		| 2018-02-10	| 490		| 19.2		| nil		|
| *G. sessile* "HW"		| P-1		| 2018-02-03	| 420		| 9.36		| nil		|
| *G. frondosa* "Charles River" | P-2		| 2018-12-29	| 420		| 68.3		| nil		|
| *G. frondosa* "Fat Moon"	| P-1		| 2018-02-10	| 840		| 43.8		| nil		|
| *H. abietis*			| P-4		| 2018-02-10	| 360		| 239.0		| nil		|
| *H. coralloides* "Cummington"	| P-2		| 2018-02-10	| 970		| 29.2		| nil		|
| *I. obliquus* "Wild"		| P-1		| 2018-02-10	| 770		| 59.4		| nil		|
| *I. resinosum* "Cummington"	| P-1		| 2018-02-10	| 890		| 20.9		| nil		|
| *L. edodes* "3782"		| P-4		| 2018-02-10	| 720		| 13.2		| nil		|
| *M. scorodonius*		| P-x		| 2018-x-y	| nil		| nil		| nil		|
| *P. roqueforti*		| P-2		| 2018-02-10	| 750		| nil		| nil		|
| *P. nameko* "JPN"		| P-1		| 2018-02-03	| 730		| 115.0		| nil		|
| *P. nameko* "Mycoterra"	| P-7		| 2018-11-20	| 600		| nil		| nil		|
| *P. columbinus* "Mycoterra"	| P-5		| 2018-11-20	| 740		| 15.2		| nil		|
| *P. erygnii*			| P-1		| 2019-02-26	| 860		| nil		| nil		|
| *P. ostreatus* "Mycoterra"	| P-5		| 2018-11-20	| 1,360		| 11.9		| nil		|
| *P. pulmonaris*		| P-x		| 2018-x-y	| nil		| nil		| nil		|
| *P. tuber-regium*		| P-2		| 2018-02-10	| 1,100		| 23.4		| nil		|
| pGreen plasmid (+)		| nil		| 2018-x-y	| nil		| nil		| nil		|
| Nuclease-free water (--)	| nil		| 2018-x-y	| nil		| nil		| nil		|


## Phylogenetic analysis

@todo


# Future work

Anthropogenic mass extinction fundamentally changes the environment and accelerates the rate of random mutations.
Therefore it's necessary to guarantee the persistence and integrity of as many beneficial genomes as possible.


## Reconstructing helpful biomolecules

@todo


## Lorem ipsum dolor sit amet

@todo:
Reconcile this paper's budding from another closely related one.
