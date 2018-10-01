# CougSat1-Readme
This contains links to every applicable file locating in the other repositories

[CougSat1-Design](https://github.com/CougsInSpace/CougSat1-Readme/blob/master/CougSat1-Design.pdf) gives an overview of CougSat-1

[CougSat1-Requirements](https://github.com/CougsInSpace/CougSat1-Readme/blob/master/CougSat1-Requirements.pdf) gives all of the system level requirements and subsystem design requirements

## Table of Contents ##
- [Hardware](#hardware)
- [Software](#software)
- [Everything else](#resources)

## Hardware ##
The [CougSat1-Hardware](https://github.com/CougsInSpace/CougSat1-Hardware) repository contains all engineering files that deal with hardware. *Note:* Every schematic's first page is the block diagram that abstracts the subsystem to blocks that should be understandable my most people (even without an electrical background).
- The [Avionics board](https://github.com/CougsInSpace/CougSat1-Hardware/tree/master/CougSat1-AvionicBoard) has the ADCS. C&DH, and IFJR subsystems.
  - [Avionics schematic](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-AvionicBoard/Documentation/Avionics.pdf)
  - [Avionics design document](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-AvionicBoard/Documentation/Avionics-Design.pdf)
- The [Backplane board](https://github.com/CougsInSpace/CougSat1-Hardware/tree/master/CougSat1-Backplane) connects every subsytems in parallel.
  - [Backplane schematic](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-Backplane/Documentation/Backplane.pdf)
  - [Backplane design document](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-Backplane/Documentation/Backplane-Design.pdf)
  - [CougSat card standard](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-Backplane/Documentation/CougSatModuleStandard.pdf) is the mechanical design of the cards that slot into the backplane
- The [Ground station](https://github.com/CougsInSpace/CougSat1-Hardware/tree/master/CougSat1-GroundStation) talks to CougSat-1
  - [Ground station schematic](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-GroundStation/Documentation/GroundStation.pdf)
  - [Ground station design document](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-GroundStation/Documentation/GroundStation-Design.pdf)
- The [Payload](https://github.com/CougsInSpace/CougSat1-Hardware/tree/master/CougSat1-Payload) is a germination experiment and a camera that will take photos of Earth
  - [Camera Payload schematic](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-Payload/Documentation/CameraPayload.pdf)
  - [Camera Payload design document](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-Payload/Documentation/CameraPayload-Design.pdf)
  - [Germination payload schematic](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-Payload/Documentation/GerminationPayload.pdf)
  - [Germination payload design document](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-Payload/Documentation/GerminationPayload-Design.pdf)
- The [Power subsystem](https://github.com/CougsInSpace/CougSat1-Hardware/tree/master/CougSat1-PowerBoard) handles all power for the entire craft
  - [EPS schematic](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-PowerBoard/Documentation/EPS.pdf)
  - [EPS design document](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-PowerBoard/Documentation/EPS-Design.pdf)
  - [Solar panel schematic](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-PowerBoard/Documentation/SolarPanel.pdf)
  - [Solar panel design document](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-PowerBoard/Documentation/SolarPanel-Design.pdf)
- The [Radio board](https://github.com/CougsInSpace/CougSat1-Hardware/tree/master/CougSat1-RadioBoard) communicates for CougSat-1 to the Ground. The +X Panel mounts the low gain antenna.
  - [Comms schematic](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-RadioBoard/Documentation/Comms.pdf)
  - [Comms design document](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-RadioBoard/Documentation/Comms-Design.pdf)
  - [+X Panel schematic](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-RadioBoard/Documentation/%2BXPanel.pdf)
  - [+X Panel design document](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-RadioBoard/Documentation/%2BXPanel-Design.pdf)
- The [Structure](https://github.com/CougsInSpace/CougSat1-Hardware/tree/master/CougSat1-Structure) holds all of the hardware together
  - [Structure design document](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-Structure/Documentation/Structure-Design.pdf)
- The [Umbilical](https://github.com/CougsInSpace/CougSat1-Hardware/tree/master/CougSat1-Umbilical) connects to CougSat-1 for testing and charging when the sun goes away
  - [Umbilical schematic](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-Umbilical/Documentation/Umbilical.pdf)
  - [Umbilical design document](https://github.com/CougsInSpace/CougSat1-Hardware/blob/master/CougSat1-Umbilical/Documentation/Umbilical-Design.pdf)

## Software ##
The [CougSat1-Software](https://github.com/CougsInSpace/CougSat1-Software) repository contains all engineering files that deal with software
- The [ADCS µController](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-ADCS) controls the ADCS
  - [ADCS software documents](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-ADCS/docs)
- The [Comms µController](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-Comms) controls the Comms subsystem
  - [Comms software documents](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-Comms/docs)
- The [Ground](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-Ground) application runs on a normal computer and talks to Comms
  - [Ground software documents](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-Ground/docs)
- The [IFJR µController](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-IFJR) controls the IFJR subsystem
  - [IFJR software documents](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-IFJR/docs)
- The [IHU](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-IHU) controls the C&DH subsystem
  - [IHU software documents](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-IHU/docs)
- The [PMIC](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-PMIC) controls the EPS
  - [PMIC software documents](https://github.com/CougsInSpace/CougSat1-Software/tree/master/CougSat1-PMIC/docs)

## Resources ##
The [Resources](https://github.com/CougsInSpace/Resources) repository contains all engineering files that are not directly related to CougSat-1. These are supplier documents, general *how to build a satellite* resources, etc.

- [Cougs in Space Inventory](https://github.com/CougsInSpace/Resources/blob/master/CougsInSpace-Inventory.xlsx) has every hardware component with its sku, model number, vendor number, and current quantity
- [Component models](https://github.com/CougsInSpace/Resources/tree/master/ComponentModels) has mCAD for every hardware component
- [CubeSat specifications](https://github.com/CougsInSpace/Resources/tree/master/CubeSatSpecifications) has the governing CubeSat specifications
- [Example cubesats](https://github.com/CougsInSpace/Resources/tree/master/ExampleCubesats) has documents from various succesful CubeSats
- [Standard Operating Procedures](https://github.com/CougsInSpace/Resources/tree/master/StandardOperatingProcedures) has documents that aid in standardizing the engineering efforts
- [Subsystems](https://github.com/CougsInSpace/Resources/tree/master/Subsystems) has resources files that are specific to a subsytem
  - [EAGLE Files](https://github.com/CougsInSpace/Resources/tree/master/Subsystems/Electronics/EAGLE%20Files) has the [EAGLE](https://www.autodesk.com/education/free-software/eagle) resource files (CAM, DRU). The readme has the guidelines for creating schematics and boards.
  - [Cougs in Space Library](https://github.com/CougsInSpace/Resources/tree/master/Subsystems/Electronics/EAGLE%20Files/CougsInSpaceLibrary) has all of the EAGLE library files. The readme has guidelines on creating a part in the library. Anyone can make a part but it may be easier to have Bradley make it.
- [Supplier Documents](https://github.com/CougsInSpace/Resources/tree/master/SupplierDocuments) has datasheets and other documents about commerical hardware (i.e. anything we do not fabricate)
- [Templates](https://github.com/CougsInSpace/Resources/tree/master/Templates) has template files for various applications
- [CubeSat 101](https://github.com/CougsInSpace/Resources/blob/master/Subsystems/General/NASACubeSat101.pdf) is a long document made by NASA that gives a starting guide to *how to build a satellite*.
