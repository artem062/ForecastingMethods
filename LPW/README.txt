This archive contains the dataset used in the following paper:

* Labelled pupils in the wild: A dataset for studying pupil detection in unconstrained environments
  Marc Tonsen, Xucong Zhang, Yusuke Sugano, Andreas Bulling
  Proc. of the 9th ACM International Symposium on Eye Tracking Research & Applications (ETRA 2016), 2016
  http://dx.doi.org/10.1145/2857491.2857520

=======================================================================================

This dataset is licensed under a Creative Commons Attribution-Noncommercial 3.0 Unported License.
See http://creativecommons.org/licenses/by-nc/3.0/ for details.
The full text of the license can be found at
http://creativecommons.org/licenses/by-nc/3.0/legalcode

BY DOWNLOADING AND USING THIS DATASET YOU AGREE TO THE TERMS OF THE ABOVE LICENSE
AND TO CITE THE ABOVE PAPERS IN YOUR OWN WORK.

You are free:
 * to Share - to copy, distribute and transmit the work
 * to Remix - to adapt the work

Under the following conditions:
* Attribution - You must attribute the work in the manner specified by the author
  or licensor (but not in any way that suggests that they endorse you or your use of the work).
* Noncommercial - You may not use this work for commercial purposes.

=======================================================================================

In case of questions please feel free to contact:
Andreas Bulling <andreas.bulling@acm.org>
http://www.andreas-bulling.eu/


=======================================================================================

Technical Description
---------------------

recording device: Pupil Pro Highspeed Eye Camera (120Hz)

There is one folder for each participant in the dataset named by the participants ID. Every participant's folder contains all the videos available from this participants named by the respective video ID, together with a txt-file with the same name containing the ground truth annotaion for that video (the annotaion for frame k is in line k in the format "x y"). Also included is a table reporting features of the recording environment for each video:
Outdoor: If true the corresponding video was recorded outdoors
Natural light: True if the video was recorded in natural light (Note: Artificial light may have been present TOO!)
Artificial light: True if the video was recorded in artifical light (Note: Natural light may have been present TOO!)
Glasses: True if the participant was wearing glasses during the recording
Contact Lensesn: True if the participant was wearing contact lenses during the recording
Prescription: Prescription values of the participant (only if known)
Nationality: Nationality of the participant
Eye color: eye color of the participant
Gender: Gender of the participant
