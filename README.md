# MoreWireless

MoreWireless is a project like "awesome wireless".
It shares awesome tools in Linux and awesome researches about wireless communication and computer network.

## Wireless Tools

These wireless tools works on Linux and are open source.

- netlink
    - iw
    - iwd
        - iwctl
    - wpa_supplicant, wpa_cli
    - hostapd
    - NetworkManager: Rely on wpa_supplicant or iwd as backend
        - Clients: nmcli, nm-connection-editor, nm-applet
    - ConnMan: Rely on iwd as backend
    - iproute2
        - ip, tc
- [Wireless Extension (wext)](https://hewlettpackard.github.io/wireless-tools/Linux.Wireless.Extensions.html)
    - [net-tools](https://net-tools.sourceforge.io) and [wireless-tools](https://hewlettpackard.github.io/wireless-tools/Tools.html) use wext API
    - wext is replaced by netlink
- Web
    - lynx

## Paper

The papers are mostly chosen from top conferences and transactions in the corresponding communities, including but not limited to SIGCOMM, MobiCom, MobiSys, SenSys, TOSN in ACM, NSDI in USENIX, and INFOCOM, IPSN, ToN, TCOM, TMC, and TWC in IEEE.

- [OFDM](./OFDM)
    - [Distributed MIMO](./OFDM/distributed_mimo.md)
    - [MAC layer](./OFDM/mac.md)
    - [Cross-technology communication](./OFDM/CTC.md)
    - [Cross-band channel estimation](./OFDM/channel_estimation.md)
    - [Congestion controller](./OFDM/congestion_controller.md)
    - [Demodulation](./OFDM/demodulation.md)
    - [Acoustic OFDM system](./OFDM/acoustic_ofdm.md)
- [LoRa](./LoRa)
    - [Distributed LoRa](./LoRa/distributed_lora.md)
    - [Multiple access](./LoRa/multiple_access.md)
    - [Adaptive LoRa link](./LoRa/adaptive_lora.md)
    - [Learning-based LoRa](./LoRa/learning_based_lora.md)
- [Backscatter Communications](./backscatter_communication)
    - [Software-Defined backscatter](./backscatter_communication/software-defined_backscatter.md)
    - [Wi-Fi backscatter](./backscatter_communication/wifi_backscatter.md)
    - [LoRa backscatter](./backscatter_communication/lora_backscatter.md)
    - [RFID and others](./backscatter_communication/RFID.md)
- [Others](./others)
    - [Distributed satellite receiver](./others/satellite_comm.md)
    - [Low-power system](./others/low_power.md)
