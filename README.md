




# Cloudiee-RC-Plane

This is an RC plane build for Fallout Event of Hackclub. This plane is my first plane to be made to enter in the aerospace. This plane is for training purpose since my next project is to make a ground control station for all kind of UAVs and autonomous or human controlled bots etc.


<img width="1200" height="1600" alt="b66bb6da-c36d-483f-9ba9-ded64c0f626d" src="https://github.com/user-attachments/assets/44e840d4-652b-4627-b1ce-6868217838ff" />

# CLOUDIEE

## Overview

This is the first RC Plane of mine I have made it with two materials 1st sunboard and 2nd depron sheet of 5mm and if it is made from sunboard it will not fly. because of the weight.Instead of purchasing a ready-made aircraft, I decided to design and build my own from scratch, learning the fundamentals of aircraft design, aerodynamics, and RC systems in the process. I also learnt about the physics behind planes and how the thrust generated helps in making the lane move forward.


---

## Project Goals
- Design and build a flyable RC aircraft from scratch
- Learn the fundamentals of aircraft design
- Understand RC electronics and radio systems
- Perform real World flight testing and tuning
- Document the entire process
- Create a platform that can be upgraded in the future with telemetry, FPV, and Autonomous capabilities


---
## Aircraft Specifications
| Parameters | Value|
|------------|------|
| Aircraft Type | Detachable RC Aircraft |
| Wingspan | 100×15 cm|
| Length | 60 cm|
| Weight | 460grams |
| Airframe Material | Depron Sheet |
| Motor | A2212 1400 Kv |
| ESC | SimonK 30A |
| Battery | ABSD 2200 mAh lipo battery |
| Servos | MicroServo 9g |
| Radio System | Flysky FS-i6 |
| Propeller | 10×4.5 R |
Note : be very specific with the choice of material to make the body use the ligtest option available with density lesser than 200 grams per 100 by 50 cm of 5 mm thickness 
<img width="1280" height="720" alt="29a50790-a8a4-493f-962d-816dea0add7d" src="https://github.com/user-attachments/assets/18d30bc0-0ee4-46c7-8f28-dddda9604810" />

NOTE: Some other things were also used such as glue gun, Thermacol cutter, Scale and other geometrical tools, Wires, XT60 connector etc

---

## Features

- Brushless motor propulsion system
- Lightweight custom airframe
- Fully controllable elevator, rudder and ailerons
- Modular electronics compartment
- Repair-friendly structure
- Removable wings for transportation
- Expandable design for future upgrades
- Designed and assembled from scratch

---

## Build Gallery
### Airframe Construction

### Electronics Installation

### Final Aircraft

### Flight Testing

More images can be found in the [media/images/](./media/images/) folder.

Photos and videos can also be found from here:

## Bill Of Materials

A complete Bill of Materials can be found in: [hardware/bom.md](./hardware/bom.md)

---

## Build Guide

### Materials

- 5mm Depron Sheet
- A2212 1400KV Motor
- SimonK 30A ESC
- 2200mAh LiPo Battery
- FlySky Receiver
- 9g Servos
- XT60 Connector
- Hot Glue

### Measurements

Wing:
100 cm × 15 cm

Length:
60 cm

### Assembly Steps

1. Cut wing sections.
2. Assemble fuselage.
3. Attach tail section.
4. Install servos.
5. Install motor.
6. Connect ESC and receiver.
7. Mount battery.
8. Test electronics.
9. Balance aircraft.
10. Prepare for flight testing.

### Wiring

Battery
↓
ESC
↓
Motor

Receiver
↓
Elevator Servo

Receiver
↓
Rudder Servo

Receiver
↓
Aileron Servo

See [hardware/bom.csv](./hardware/bom.csv) for component details.

## Electronics System
The aircraft electronics consists of:

- Brushless motor
- Electronics Speed Controller (ESC)
- LiPo Battery
- FlySky Receiver
- Servo Motors
- Control Linkages

Detailed wirings of the electronics can be found here
<img width="1175" height="661" alt="1fde0f3a-9efa-44f4-9804-6df43b7f1c4e" src="https://github.com/user-attachments/assets/6bed20d6-0b89-4f62-bf03-71f7e22f0c80" />

See [hardware/circuit-design.md](./hardware/circuit-design.md) for detailed electronics information.

---
### Lessons Learned

This project provided practical experience in:

- Aircraft design
- Aerodynamics
- Embedded electronics
- Power systems
- RC communication
- Structural engineering
- Flight testing
- Troubleshooting and iteration

More importantly, it demonstrates that successful engineering rarely works perfectly on the first attempt. Many improvements came directly from failures observed during testing and subsequent design iterations.

For detailed lessons learned, see [docs/issues-and-lessons.md](./docs/issues-and-lessons.md).

<img width="1920" height="2560" alt="6091376151566684169" src="https://github.com/user-attachments/assets/69fb4f09-a768-46d3-82f1-8c9676dad03c" />

---

## Future Improvements

Planned Upgrades include:

- FPV camera system
- Onboard telemetry
- GPS tracking
- Flight stabilization system
- Custom Ground Control Station
- Autonomous waypoint navigation
- Improved airframe efficiency
- Long range communication system

---

## Repository Structure

```
cloudiee-rc-plane/
├── README.md
├── hardware/
│   ├── README.md
│   ├── bom.md
│   ├── bom.csv
│   ├── designs.md
│   ├── circuit-design.md
│   └── cad/
│       └── README.md
├── firmware/
│   └── README.md
├── docs/
│   ├── README.md
│   ├── journal.md
│   ├── how-it-work.md
│   └── issues-and-lessons.md
├── media/
│   ├── README.md
│   ├── images/
│   │   └── gallery.md
│   └── videos/
│       └── demo-links.md
└── pcb/
    └── README.md
```

---
### Acknowledgements

Special thanks to the Hack Club community and their event called Fallout for which I am glad to be a part of.


<img width="1200" height="1600" alt="b66bb6da-c36d-483f-9ba9-ded64c0f626d" src="https://github.com/user-attachments/assets/6c1bea11-0a89-47c0-87b4-5e9738561558" />
