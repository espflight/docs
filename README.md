# ESPFlight Documentation

**Documentation and guides for the ESPFlight platform.**

This repository contains the official documentation for learning, building, configuring, testing, and developing ESP-based drones with ESPFlight.

ESPFlight documentation is intended for enthusiasts, students, educators, Makers, developers, and engineers.

## Start with ESPFlight v1.0

If you are building the current public v1.0 platform, start here:

**[Build ESPFlight v1.0](BUILD_V1.0.md)**

The v1.0 baseline uses:

- ESPFlight Firmware v1.0.0
- ESPFlight Hardware Reference v1.0
- ESPFlight Application v1.0.0
- ESPFlight Protocol 2

The build path links the public EasyEDA hardware source, validated GitHub Releases, Android application, firmware setup, and pre-flight validation steps in one place.

## Documentation

The documentation covers:

* Getting Started
* Hardware Guide
* Assembly
* Firmware Setup
* ESPFlight Application
* Configuration
* First Flight
* Assisted Flight
* Safety and Validation
* Troubleshooting
* Development and experimentation

## Getting Started

If you are new to ESPFlight, start with the v1.0 build path above.

A typical ESPFlight workflow is:

1. Build or prepare compatible hardware.
2. Configure and flash ESPFlight Firmware.
3. Validate the hardware and control directions.
4. Connect using the ESPFlight Application.
5. Perform safety checks.
6. Proceed to controlled flight testing.

## ESPFlight Components

ESPFlight combines:

* Open-source flight firmware
* Open hardware reference designs
* ESPFlight Application
* Documentation and build guides

Together, these components provide a practical foundation for learning, experimenting with, and developing ESP-based drones.

## Safety

ESPFlight is an experimental and educational platform that controls real motors and flying hardware.

Always validate your hardware configuration before powered flight.

When appropriate:

* Test without propellers first.
* Verify motor order and direction.
* Verify propeller direction.
* Verify IMU orientation.
* Verify control directions.
* Verify ARM / DISARM behavior.
* Verify failsafe behavior.
* Keep people, animals, and property clear during testing.

Always follow applicable laws and safety requirements.

### Network security

ESPFlight Protocol 2 is intended for use on trusted local Wi-Fi networks. The v1 control and telemetry transport does not provide encrypted or authenticated protection against hostile clients on the same network. Use a private, trusted network for flight control and testing.

## Licensing

Except where otherwise noted, ESPFlight Documentation is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

The ESPFlight name, logo, and other brand assets are not included in this license.

See [LICENSE.md](LICENSE.md) for details.

## ESPFlight

**Learn it. Build it. Change it. Create your own.**

https://espflight.com
