![](https://img.shields.io/badge/Working-yes-green)
![](https://img.shields.io/badge/Latest%20supported-Big%20Sur%2011.2-blue)

# 840-G3 with Big Sur 11.2 & bootloader OC-0.6.7
Basic EFI for Opencore 0.6.7 with macOS Big Sur (last working update 11.2.3)

swapped network card (DW1560) with extra kexts :
* AirportBrcmFixup
* BrcmBluetoothInjector
* BrcmFirmwareData
* BrcmPatchRAM3

No kext for SD Card reader or Fingerprint sensor (I don't use them)

## Working components

| Component | Component model | State |
| --- | --- | --- |
| Wifi | DW1560 | Working (also Airdrop) |
| Bluetooth | DW1560 | Working |
| Graphics | Intel HD Graphics 520 | Working |
| Sound | Bang & Olufsen | Working|
| Battery | / | Working |
| Trackpad | Synaptics | Workingwith gestures |
