# How Cloudiee Works

## Introduction

Cloudiee is a detachable fixed-wing RC aircraft built from scratch using commonly available materials such as sunboard and Depron sheet. The aircraft is controlled using a FlySky FS-i6 transmitter and uses a brushless propulsion system for thrust generation.

The purpose of this project was to learn the fundamentals of RC aircraft construction, electronics integration, aerodynamics, and aircraft design before moving on to more advanced aerospace projects such as a custom UAV Ground Control Station.

---

## Main Components

The aircraft consists of five major systems:

1. Airframe
2. Radio Control System
3. Propulsion System
4. Power System
5. Control Surface System

---

## Airframe

The airframe forms the structure of the aircraft.

Materials used:

- Sunboard
- 5 mm Depron Sheet

The aircraft dimensions are:

| Parameter | Value |
|------------|------------|
| Wingspan | 80 cm |
| Wing Chord | 15 cm |
| Length | 58 cm |

The wings are detachable which makes transportation and storage easier.

---

## Radio Control System

The aircraft is controlled using:

- FlySky FS-i6 Transmitter
- FlySky Receiver

The transmitter sends radio signals to the receiver mounted inside the aircraft.

These signals contain instructions from the pilot and are used to control:

- Elevator
- Rudder
- Ailerons
- Motor Throttle

Flow:

Pilot Input
↓
FlySky FS-i6
↓
Receiver
↓
Servos / ESC
↓
Aircraft Movement

---

## Propulsion System

The propulsion system consists of:

- A2212 1400KV Brushless Motor
- SimonK 30A ESC
- 10×4.5 Propeller

The brushless motor rotates the propeller which generates thrust.

The generated thrust moves the aircraft forward allowing the wings to create lift.

---

## Power System

The aircraft uses:

- ABSD 2200mAh LiPo Battery

The battery powers:

- ESC
- Receiver
- Servos
- Motor

Power Flow:

Battery
↓
ESC
↓
Motor

Battery
↓
Receiver
↓
Servos

---

## Control Surfaces

The aircraft uses three primary control surfaces.

### Elevator

Controls pitch.

- Nose up
- Nose down

### Rudder

Controls yaw.

- Left turn
- Right turn

### Ailerons

Controls roll.

- Left banking
- Right banking

The servos move these control surfaces based on commands received from the transmitter.

---

## Challenges Encountered

During construction several challenges were observed:

### Weight

The biggest challenge was aircraft weight.

The wing alone weighs approximately 346 grams.

The overall airframe became significantly heavier than expected due to the use of sunboard.

This may prevent successful flight because the aircraft could require more lift than the wing can generate.

### Material Selection

While sunboard provides strength, it has much higher density than Depron foam.

For future versions:

- Depron
- Styrofoam
- Lightweight foamboard

will be preferred.

### Balance and Center of Gravity

Proper aircraft balance is essential.

Incorrect weight distribution can cause:

- Nose-heavy behaviour
- Tail-heavy instability
- Poor flight performance

---

## Current Status

Current Progress:

✓ Wing Construction Complete

✓ Fuselage Complete

✓ Electronics Installed

✓ Motor Testing Complete

✓ Servo Testing Complete

✓ Wiring Complete

✓ Repository Documentation Started

Pending:

- Final CG Verification
- Maiden Flight Test
- Weight Optimization
- Airframe Improvements

---

## Future Improvements

Planned upgrades include:

- Lightweight airframe redesign
- FPV camera system
- Telemetry support
- GPS integration
- Flight stabilisation
- Long-range communication
- Custom UAV Ground Control Station

Cloudiee serves as the foundation for future aerospace and UAV projects.
