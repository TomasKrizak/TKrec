TKReconstruct is a first implementation of the new tracking as a Falaise module. Currently it is based on TKEvent library. This is only a testing version, not the final implementation!

TKReconstruct module takes CD bank as an input a creates a reconstruction using TKEvent library. The found clustering solution and trajectory solution is stored in TCD and TTD data banks. 

To obtain the final PTD bank you then need to apply Charged Particle Tracking module that extrapolates the verteces and creates the PTD bank.

