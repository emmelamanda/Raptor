# Raptor Perception of Mismatch in Seasonally Polyphenic Prey

### In Review 

### Authors: Amanda Emmel, L. Scott Mills, Nate Bickford

### Please contact first author with questions about the code, data, or experiments: emmel.amanda@gmail.com

## Abstract
Climate change effects on predator-prey interactions are poorly understood, with few study systems that explicitly connect antipredator traits to climate drivers. Within 21 seasonally color polyphenic species, most populations molt into a winter white coat to camouflage with seasonal snow, however some individuals and populations remain invariant brown throughout the year. Using falconry-trained goshawks (Accipiter atricapillus), we experimentally evaluate how raptors perceive white and brown lures with varying background matching and assess how motion and habitat influence attack distance. We find that mismatch influences raptor detection of stationary models, but not moving lures. Attack distances were greater in open habitats compared to forest. Mismatch with substrate significantly increased detectability of white hare models relative to mismatched brown hare models, suggesting unequal predation risk for mismatched white and brown morphs. Our results may imply fitness differences for winter white and invariant brown morphs of seasonally polyphenic species under future climate scenarios.

DATA: gos_lures.csv\  
CODE: goshawk_lures.Rmd

## Variables

ID: Goshawk name

Order: Ordered number of repeated experimental trial starting at 1 and repeating with every individual trial. Moving lure and stationary model trials are each numbered separately beginning at 1.

Rep: 1 or 2 reflects whether this individual trial was the first or 2nd repetition at each experiment location (trials were repeated once with each color model/lure at each location, initial color was randomly selected for each location prior to experiments).

Cover: O - Open habitat (Meadow with dead grass)\   
       F - Forest habitat (Ponderosa forest with sparse understory)

Ground: B - Brown, bare ground i.e. meadow or forest floor\  
        W - White, snowy ground

Lure: B - Brown wild-type agouti rabbit pelt\  
      W - White rabbit pelt

Motion: M - Moving lure\
        S - Stationary model

Dist: Attack distance (meters) or distance between hawk take-off and lure/model capture location.
