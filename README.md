# scramble
Melody Scrambler / Remixer for MIDI ... Final project for WACM

Takes a melody specified in MIDI and performs various tranformations on the melody.
Probabilities are assigned to the various transformations, with statistical feedback being used to 
choose which tranformation to perform.

Parameters in RunStatisticalFeedbackMultiTrack:

  alpha_statFeedback : higher value leads least-recently chosen transformation to have highest prob
  weights : probabilities for various transformations
  numRuns : number of transformations
