# gigabyte-b75m-d3v-opencore

This repo contains all the files required for Opencore 0.8.3 on the Gigabyte B75M D3V Motherboard with the following hardware;

- Gigabyte B75M D3V
- Intel i5 3550 (Ivy Bridge)
- Realtek Gigabit Ethernet
- Realtek ALC 887
- AMD Radeon RX 580

This config supports;

- iMac Pro
- Filevault
- Bluetooth & WiFi (with supported card)
- Latest version of OpenCore 0.8.3

Things that need changing is;

- Power Management for the cpu, as unless you have i5 3550 then this probably will cause a panic (https://github.com/Piker-Alpha/ssdtPRGen.sh)
- Serials numbers so icloud etc works


Also included is a modded Bios file for flashing
`mod_B75MD3V.f13`