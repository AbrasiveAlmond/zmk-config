# Flash firmware
iPut the microcontroller into dfu mode by double tapping the reset button within one second. A new drive will mount. Drag and drop the corresponding  USB Flashing Format (UF2) file onto the drive. Once the process is complete, it will unmount and be running the new firmware.
Reset the microcontroller then it should appear as a drive on your computer, drag and drop the corresponding firware file (.uf2) to flash it.
The firmware files can be found as artifacts from GH actions.

[Note] 
  For split keyboards, only the central (left) side will need to be reflashed if you are just updating your keymap. More troubleshooting information for split keyboards can be found here.
