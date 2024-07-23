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
R version 4.3.2 (2023-10-31) "Eye Holes"
Packages: dplyr, ggplot2, AICcmodavg, gclus, SASmixed, Matrix, lme4, lmerTest, tidyr


