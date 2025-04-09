## STUDY SUMMARY
This repository contains code and data for the project:

### Raptor Perception of Mismatch in Seasonally Polyphenic Prey

**Citation**:

**Authors**: Amanda Emmel (1*), Dr. Nate Bickford (2), Dr. L. Scott Mills (1)

**Affiliations**

1: Wildlife Biology Program, Department of Ecosystem and Conservation Sciences, University of Montana, Missoula MT 59812

2: Natural Sciences Department, Oregon Institute of Technology, Klamath Falls OR 97601

*correspondence to: emmel.amanda@gmail.com

Data collection: Nate Bickford, Amanda Emmel

Code: Amanda Emmel

In this study, we use falconry-trained goshawks (Accipiter atricapillus) to experimentally evaluate how raptors perceive white and brown lures in snowy and bare ground conditions and assess how motion and habitat influence attack distance. 

### Analysis Summary
We fitted linear mixed effects models to relate attack distance (m) to mismatch and habitat structure. Attack distance (y, meters) was the response in all models, and all models included a random intercept α_j accounting for individual variation between goshawks. Fixed effects include mismatch as an interaction between two covariates: lure color (x_1) and ground color (x_2), learning (x_3i) represented by ordered trial number for each individual bird, and habitat structure (x_4, open or forest). Moving lure and stationary model trials were analyzed separately given differences in experiment format.



## ACCESS INFORMATION
1. MIT License
2. Recommended citation for this data/code archive
xxx

## DATA & CODE FILE OVERVIEW
This data repository consist of 1 data files, 1 code scripts, 1 license, and this README document, with the following data and code filenames and variables

Data files and variables
    1. gos_lures.csv 
    
### Variables

**ID**: Goshawk name

**Order**: Ordered number of repeated experimental trial starting at 1 and repeating with every individual trial. Moving lure and stationary model trials are each numbered separately beginning at 1.

**Rep**: 1 or 2 reflects whether this individual trial was the first or 2nd repetition at each experiment location (trials were repeated once with each color model/lure at each location. initial color was randomly selected for each location prior to experiments).

**Loc**: Ordered experiment location numbers (locations selected opportunistically in the field by the falconer). Since trials were repeated once with each color model/lure at each location, for each Location there are 2 Reps.

**Cover**:    O - Open habitat (Meadow with dead grass)     
              F - Forest habitat (Ponderosa forest with sparse understory)

**Ground**:   B - Brown, bare ground  
              W - White, snowy ground

**Lure**:     B - Brown wild-type agouti rabbit pelt    
              W - White rabbit pelt

**Motion**:   M - Moving lure  
              S - Stationary model

**Dist**: Attack distance (meters) or distance between hawk take-off and lure/model capture location.

## Code scripts and workflow
 1. goshawk_lures.Rmd
    
    Data formatting and analysis using linear mixed effects models to assess effects on goshawk atack     
    distance

**SOFTWARE VERSIONS**

R version 4.4.3 (2025-02-28) "Trophy Case"  
Packages: dplyr (version 1.1.4), ggplot2 (version 3.5.1), AICcmodavg (version 2.3-4), gclus (version 1.3.3), SASmixed (version 1.0-4), Matrix (version 1.7-2), lme4 (version 1.1-36), lmerTest (version 3.1-3), tidyr (version 1.3.1), merTools (version 0.6.2), MASS (version 7.3-64)

**PERMITTING**

All experimental protocols were approved through the University of Montana Institutional Care and Use Committee (Protocols No. 028-21SMRCS-051121, 000-000A-029). Participating falconry goshawks were privately owned and cared for.

**FUNDING**

Funding for this work provided by National Science Foundation Division of Environmental Biology Grant 1907022 to Dr. L. Scott Mills




