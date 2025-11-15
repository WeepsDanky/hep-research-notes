# Physics performance 

The physics performance is anchored in a highly efficient background suppresion. All physics sensitivity are based on 2E+20 protons on target. 

## Simulation and reconstruction

* studies using GEANT-based Monte-Carlo framework, based on FairRoot package and is called FiarShip. 
  * GEANT4 simulate particles through the target and experimental setup
  * PYTHIA8 for the primary proton fixed target interaction 
  * PYTHIA6 for muon deep inelastic scattering (DIS) and cascade production of charm and beauty 
  * GENIE for interaction of neutrinos 
  * production and decays of various types of FIPs have been implemented in FairShip, mainly used PYTHIA8 to generate different signal processes
* simulateed 6.5E+10 protons on target with energy cut of 10 GeV for transporting particles after hadron absorber, with strongly enhanced muon production from QED process such as resonance decays and gamma conversion. 
  * simulation samples give sufficient statistics after muon shield for background determination to be extrapolated to full run of BDF/SHiP with good accuracy
* neutrino DIS: use GENIE generator to force neutrino to interact with material distribution of setup to simulate background
* validity of FairShip prediction verified by comparing to data from CHARM beam-dump experiment at CERN and cross-check in summer 2018 at CERN SPS in good agreement


Goal of SHiP: 

* accurate determination mass of potential hidden sector candidate 
* accurate vertex and momentum resolution to suppress background 
  * discriminate signal tracks from common vertex from background from random combination of tracks 
  * distance of closest approach (DOCA) between tracks used to suppress background 
  * GENFIT used for reconstruction of tracks in FairShip

## Muon shield performance 

Goal: reduce initial flux of 10E+11 muons per proton spill by up to six orders of magnitude. 

Structure: magnetisation of hadron absorber and chain of six normal-conducting magnets (shaped optimized by machine learning and iterative simulation of muon background sample to minimize muon flux through SND detector and HSDS detector)

Future To do: shorten muon shield by downscale magnetics due to small space in ECN3 

Problem: with shortened muon shield, the rate within target is higher. 

Solution:

1. performing a full optimization of muon shield by machine learning. 
2. Use superconducting (SC) magnetics which have stronger field, potentially: 
   1. A one-magent solution with unconfined return field
   2. alternate polarity two-magnet solution with confined field

## FIP decay search performance

