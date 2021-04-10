![](https://img.shields.io/badge/Working-yes-green)
![](https://img.shields.io/badge/Latest%20supported-Big%20Sur%2011.2-blue)

# 840-G3 with Big Sur 11.2.3 & bootloader Opencore 0.6.8
Basic EFI for Opencore 0.6.7 with macOS Big Sur (last working update 11.2.3)

swapped network card (DW1560) with extra kexts :
* AirportBrcmFixup
* BrcmBluetoothInjector
* BrcmFirmwareData
* BrcmPatchRAM3

### Working

| Component | Component model | State |
| --- | --- | --- |
| Wifi | DW1560 | Working (also Airdrop) |
| Bluetooth | DW1560 | Working |
| Graphics | Intel HD Graphics 520 | Working |
| Sound | Bang & Olufsen | Working|
| Trackpad | Synaptics | Working with gestures |
| Battery | / | Working |

### Not Working
I don't use these, so I didn't invest in the kexts

| Component | State |
| --- | --- |
| SD Card Reader | Not Working |
| Fingerprint Sensor | Not Working |
