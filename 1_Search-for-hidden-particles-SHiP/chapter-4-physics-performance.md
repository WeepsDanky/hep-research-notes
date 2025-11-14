# Physics performance 

The physics performance is anchored in a highly efficient background suppresion. All physics sensitivity are based on 2E+20 protons on target. 

## Simulation and reconstruction

* studies using GEANT-based Monte-Carlo framework, based on FairRoot package and is called FiarShip. 
  * GEANT4 simulate particles through the target and experimental setup
  * PYTHIA8 for the primary proton fixed target interaction 
  * PYTHIA6 for muon deep inelastic scattering (DIS) and cascade production of charm and beauty 
  * GENIE for interaction of neutrinos 
  * production and decays of various types of FIPs have been implemented in FairShip, mainly used PYTHIA8 to generate different signal processes
* simulateed 6.5E+10 protons on target with energy cut of 10 GeV for transporting particles after hadron absorber 