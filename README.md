# GOSH-FHIRworks2020-PatientInfoVR
VR/Unity/C# Project showing Patient Data from GOSH (Great Ormond Street Hospital) DRIVER'S FHIR (Fast Healthcare Interoperability Resources) Server on top of a 360° Playback inside a Virtual Reality environment.

## What project does
- 360° video-player that allows you to:
  - Play/Pause/Stop video
  - Change volume
  - Look around using mouse (or using a virtual headset)
  - Type in Patient ID, which will then play that Patient's surgery video*
  - Click on a button that displays patient information while video is playing
  
*Videos used in the project are random surgery videos taking online, which have no association with the Patient's data displayed and are only used for demonstration purposes

## How project works
- 3 Unity Scripts:
  1. **Api** (Connects to FHIR API, Updates & Displays Patient Info)
  2. **VideoManger** (Implements Play, Pause Stop, Change Volume & "Inputfield to Video" functionalities)
  3. **LookAround** (Allows user to move around the video using computer mouse, for convenience)

## Requirements to run project in Unity

1. Create new Unity project
2. Import package
3. Use https://github.com/greenfrogs/FHIRworks_2020?fbclid=IwAR3v1f3RUjr5u9NdqqgEkHKxcHHVwCtO9A2NRHjsrCzZ_BiMjDSHOsfXMVY to set up access to the GOSH DRIVE's FHIR Server
4. Hit `Play` button in Unity to run the demonstrator
