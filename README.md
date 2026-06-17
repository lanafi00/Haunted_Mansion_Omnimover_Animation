
# Haunted Mansion Omnimover Simulation
### Autodesk Maya · Ride Systems · Human Factors Engineering
 
A simulation of the Disneyland **Haunted Mansion** attraction's omnimover vehicle system, built in Autodesk Maya.

<img width="421" height="453" alt="image" src="https://github.com/user-attachments/assets/c5713557-f35a-4188-b7fd-217fe0f231f4" />
<img width="389" height="390" alt="image" src="https://github.com/user-attachments/assets/90339dc4-9c9a-4dac-a129-a21cc3197b1e" />
<img width="727" height="399" alt="image" src="https://github.com/user-attachments/assets/cf483d29-343d-4bc6-9391-4de3109850e9" />

---
 
## Features
 
### Track & Vehicle System
- Track curve replicating the Haunted Mansion layout
- Imported and rigged ride vehicle geometry
- Procedural vehicle motion driven by MEL scripting and manual yaw keyframing 
### Real-Time HUD Telemetry
- Overlay displaying per-vehicle **position (feet along curve)**, **orientation (degrees yaw rotation)**, and **velocity (feet/sec)** throughout the ride cycle
- Updates in real time during playback  
### Human Factors & Clearance Analysis
- Rigged **Dreyfuss 99th-percentile anthropometric model** seated within the vehicle
- Custom **clearance envelope** geometry surrounding the vehicle to model worst-case occupant reach  
- Designed to flag spatial conflicts between guests and surrounding architecture
### Camera System
- **POV cameras** mounted to vehicles for a guest's-eye view of the ride
- **Follow cameras** tracking individual vehicles through the environment
---
 
## Technical Details
 
| Component | Tool / Method |
|---|---|
| Track system | Maya NURBS curve + motion path rig |
| HUD telemetry | MEL scripting |
| Velocity calculation | Derived from curve parameterization |
| Anthropometric model | Dreyfuss 99th-percentile reference figure |
| Clearance envelope | Custom geometry rig tied to vehicle transform |
| Cameras | Per-vehicle POV + follow camera rigs |
 
---
 
## Attribution
 
Environmental geometry includes assets sourced from free online resources. All rigging, animation systems, HUD implementation, and human factors modeling are original work.
 
---
 
 
