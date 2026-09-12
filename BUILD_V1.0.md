# Build ESPFlight v1.0

This page is the shortest official path for building and validating the ESPFlight v1.0 platform baseline.

## v1.0 baseline

Use these versions together:

- **ESPFlight Firmware v1.0.0**
- **ESPFlight Hardware Reference v1.0**
- **ESPFlight Application v1.0.0**
- **ESPFlight Protocol 2**

## 1. Review the hardware

Start with the ESPFlight Hardware Reference v1.0.

- EasyEDA project: https://oshwlab.com/eng_karimizadeh/project_xfbshxkb
- Hardware repository: https://github.com/espflight/hardware
- Hardware v1.0 release: https://github.com/espflight/hardware/releases/tag/v1.0

Review the schematic, PCB, BOM, assembly notes, module requirements, power connections, and pin assignments before building or ordering hardware.

## 2. Build and inspect the hardware

Use the validated Hardware v1.0 fabrication files or adapt the open reference design for your own compatible board.

Before applying power:

- inspect solder joints and assembly;
- check for shorts;
- verify supply voltage and polarity;
- verify installed modules and connections.

Perform initial validation without propellers where appropriate.

## 3. Download and configure the firmware

- Firmware repository: https://github.com/espflight/firmware
- Firmware v1.0.0 release: https://github.com/espflight/firmware/releases/tag/v1.0.0

Follow the firmware `BUILDING.md` guide to prepare the Arduino environment, configure `config.h`, compile, and flash the controller.

The published v1.0.0 tag remains the release baseline. For the documentation correction related to the assisted-Landing application ramp, see `ERRATA_v1.0.0.md` in the Firmware repository.

## 4. Install the ESPFlight Application

ESPFlight Application v1.0.0 is the validated Android application for the v1.0 baseline.

- Application page: https://espflight.com/app/
- Application repository: https://github.com/espflight/application
- Application v1.0.0 release: https://github.com/espflight/application/releases/tag/v1.0.0
- Direct APK: https://github.com/espflight/application/releases/download/v1.0.0/ESPFlight_Application_v1.0.0.apk

Only install the official APK distributed through ESPFlight channels.

## 5. Connect on a trusted local network

ESPFlight Protocol 2 uses local Wi-Fi communication.

The v1 control and telemetry transport does not provide encrypted or authenticated protection against hostile clients on the same network. Use a private, trusted local network for flight control and testing.

## 6. Validate before flight

Before installing propellers or attempting controlled flight, verify:

- motor order and motor direction;
- propeller direction;
- IMU orientation;
- control directions;
- ARM / DISARM behavior;
- telemetry and connection status;
- communication failsafe behavior;
- battery and power behavior;
- any altitude-sensing hardware used by assisted flight.

## 7. First controlled flight

Move to a safe, open test area only after bench validation passes.

Start conservatively, keep people, animals, and property clear, and follow applicable local laws and safety requirements.

## Need more detail?

Website and documentation:

https://espflight.com/docs/

Project website:

https://espflight.com

---

**Learn it. Build it. Change it. Create your own.**
