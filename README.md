# ESPFlight Documentation

**GitHub release/build entry point for the ESPFlight documentation ecosystem.**

This repository provides the stable GitHub-facing documentation needed to identify, build, and validate the published ESPFlight platform baseline.

The complete user documentation is currently published at:

https://espflight.com/docs/

## Repository scope

This repository is intentionally smaller than the full website documentation source.

It currently contains:

- the stable ESPFlight v1.0 build path;
- repository-level documentation licensing information;
- links to the complete maintained documentation website.

The website documentation covers the detailed learning and reference material, including Getting Started, hardware, assembly, firmware setup, the ESPFlight Application, configuration, first flight, assisted flight, safety, troubleshooting, and development guidance.

This repository should therefore be treated as the **versioned GitHub entry point and release/build reference**, while the website is the **complete user-facing documentation experience**.

If the full website documentation source is moved into this repository in the future, this scope statement must be updated at the same time so there is only one clearly defined source-of-truth model.

## Start with ESPFlight v1.0

For the current public v1.0 platform, start here:

**[Build ESPFlight v1.0](BUILD_V1.0.md)**

The validated v1.0 baseline uses:

- ESPFlight Firmware v1.0.0
- ESPFlight Hardware Reference v1.0
- ESPFlight Application v1.0.0
- ESPFlight Protocol 2

The build path connects the public EasyEDA hardware source, validated GitHub Releases, Android application, firmware setup, network-security note, and pre-flight validation steps.

## Typical workflow

1. Build or prepare compatible hardware.
2. Configure and flash ESPFlight Firmware.
3. Validate the hardware and control directions.
4. Connect using the ESPFlight Application.
5. Perform safety checks.
6. Proceed to controlled flight testing.

For detailed instructions at each step, use the complete documentation website.

## Safety

ESPFlight is an experimental and educational platform that controls real motors and flying hardware.

Always validate your hardware configuration before powered flight. Test without propellers where appropriate, verify motor order and direction, verify propeller direction, verify IMU orientation and control directions, verify ARM / DISARM and failsafe behavior, and keep people, animals, and property clear during testing.

Always follow applicable laws and safety requirements.

## Network security

ESPFlight Protocol 2 is intended for use on trusted local Wi-Fi networks. The v1 control and telemetry transport does not provide encrypted or authenticated protection against hostile clients on the same network.

Use a private, trusted network for flight control and testing.

## Licensing

Except where otherwise noted, ESPFlight Documentation is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

The ESPFlight name, logo, and other brand assets are not included in this license.

See [LICENSE.md](LICENSE.md) for details.

## ESPFlight

**Learn it. Build it. Change it. Create your own.**

https://espflight.com
