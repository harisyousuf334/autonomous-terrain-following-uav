# autonomous-terrain-following-uav
An exploration into an autonomous aircraft system capable of maintaining a desired clearance from changing terrain — inspired by how terrain-following radar allows aircraft to fly close to the ground while automatically adjusting to the landscape below.

Overview
This project investigates a sensor-based approach to terrain-following flight, where an aircraft continuously adjusts its altitude in response to real-time distance measurements rather than relying on pre-mapped terrain data.

Proposed Architecture
Downward-facing distance sensor — measures ground clearance directly beneath the aircraft
Forward-facing ranging system — detects upcoming terrain changes ahead of the aircraft's flight path, allowing for anticipatory adjustments rather than purely reactive ones

Proof of Concept

An initial proof-of-concept was built to test the core feedback loop:

Hardware: Arduino Nano + ultrasonic distance sensor
Goal: Experiment with maintaining a constant height above a surface using real-time sensor feedback
Focus: Validating that sensor readings could reliably drive height-correction behavior before adding flight-control complexity

Control Surface Investigation

Began investigating how sensor input could be translated into control-surface adjustments (e.g. elevator/throttle response) to actually change aircraft altitude in response to terrain — connecting the sensing layer to an actuation layer.

Project Status

🚧 Paused — development paused while building up further programming skills needed to expand the control system. Core sensor feedback concept was validated; next steps involve implementing full control-surface logic and testing on a physical airframe.

Future Work
Resume control-surface integration
Test forward-facing ranging sensor for anticipatory terrain detection
Move from bench-top proof-of-concept to a physical test platform












