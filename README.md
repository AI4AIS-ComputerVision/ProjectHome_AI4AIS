# Home Project to AI4AIS
Univeristà Politecnica delle Marche - Pietro Rignanese, Andrea Polenta e Francesco Pio Bocci

Progetto di *Computer Vision and Deep Learning*

Prof: Emanuele Frontoni<br>
Tutor: Adriano Mancini e Alessandro Galdelli

------------------------------------------------------------------------------------------------

# Title Project: Classification of fishing activities from AIS data
The research project took care of classifying types of fishing, based on the AIS dataset, acquired by the CNR for the purpose of:<br>
  * understand the behavior of fleets and classify their fishing activities using Machine Learning techniques from AIS data (*position, speed, time ,course over ground*)

### What is AIS?
AIS (Automatic Identification System) is an automatic tracking system that uses transponders on ships and is used by Vessel Traffic Services (VTS). 
AIS does this by continuously transmitting  (every 5 minutes) vessels’ position, identity, speed and course, along with other relevant information, to all other AIS equipped vessels within range.  

#### Type of fishings:
  * LLD: Drifting Longline
  * LLS: Set Longline
  * OTB: Bottom Otter Trawl
  * PS: Purse Seine
  * PTM: Midwater Pair Trawl
  * TBB: Beam Trawl

------------------------------------------------------------------------------------------------------

## Motivation and Goals
* We propose new techniques to process position data, extracting vessel trips and recognizing fishing activities, at the current stage of development, also mapping the harbors at the beginning and end of a fishing session.
* The ability to map (even in real time) the ships allows to detect illegal activities or to certify the area where a certain ship has carried out its fishing activities.
