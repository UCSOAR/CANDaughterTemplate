## If project is not recognized, try opening the .project File Directly from File Explorer, so that it gets re-imported into stm32cubeIDE

The CANBus daughter board is initialized in the CANBusTask InitTask. This repository is built for G4, but the setup for the H7 is the exact same except for the version of the FDCan driver used in the SoarDrivers submodule. The H7 uses the H7 FDCAN driver folder in SoarDrivers, while the G4 uses the G4 FDCAN driver folder in SoarDrivers.
