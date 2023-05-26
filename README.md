# Anycubic-Predator-Klipper-Configuration
A working configuration and klipper binary for use with the Anycubic Predator and its original TriGorilla-Pro control board

# Setup
 - Firstly you will need to flash the klipper firmware to the trigorilla board. This can be done by following the instructions on [this](https://github.com/SXHXC/Marlin-Anycubic-Predator-Trigorilla-PRO) page; using the provided klipper.bin file as the source.
 - After uploading the board should be able to connect to the klippy host software (do note that the screen has not been configured, so it will remain black).
 - Some reasonable delta parameters have been prepared for a default Predator, but you will now need to perform calibration.

# Calibration
  - Start by performing a [probe calibration](https://www.klipper3d.org/Probe_Calibrate.html)
  - Then you must run basic [delta calibration](https://www.klipper3d.org/Delta_Calibrate.html?h=delta+calibration)
  - After performing basic delta calibration you can continue down the page to advanced calibration, the settings I used were a scale factor of 1.6, and print speed of 40mm/s
