# An attempt to understand zebra finch communication in a controlled but natural environment. Program is ongoing, although no new data is being collected at this time (6/2024)

## There is code to:
 *) Run arduinos that control feeding and artificial predator (harmless) presentations
 
 *) Merge and align auditory recordings from FM wireless microphones recorded in Software Defined Radio (SDR)
  <img width="468" alt="alignment" src="https://github.com/billewood/truman/assets/6302741/21e60ec4-e94d-4df0-8964-3277bab70273">

 *) Track birds in 3D space using arrival times of auditory pings that are produced in an 8 speaker array
 <img width="468" alt="localization_raw" src="https://github.com/billewood/truman/assets/6302741/937dc1f0-5d17-4857-93cd-2f71418a7e9e">

 *) Vocalizations are currently segmented using soundsep https://github.com/theunissenlab/soundsep2
 
 *) Cluster vocalizations into call categories
 <img width="468" alt="clustering" src="https://github.com/billewood/truman/assets/6302741/bd86abd6-489a-4c46-9928-72000d0e2bef">

 *) Analyze behavior and vocalizations
<img width="1095" alt="Screenshot 2024-06-06 at 10 14 33 AM" src="https://github.com/billewood/truman/assets/6302741/64a27cb5-d832-412d-856e-8a18e524b730">

### Background
Decoding/understanding other species' vocalizations will require first understanding what those species are doing and then correlating those behaviors with their vocalizations.
My technique is to track animals constantly, force particular behaviors with an automated environment that logs events, and then use large data to correlate the vocalizations. 
The obvious species to do this with are zebra finches, as they are extremely social and extremely vocal.
