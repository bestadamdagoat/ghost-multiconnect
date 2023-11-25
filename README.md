<p align="center">
<a href="https://www.ghostcontrols.com/"><img src="https://raw.githubusercontent.com/bestadamdagoat/ghost-multiconnect/main/assets/ghost_logo-01_4000x.webp" ></a>
</p>


# Ghost MultiConnect

The Ghost MultiConnect is a device made by Remootio that allows you to control your gate through your mobile device. It is not part of the series of Remootio devices and is a little different in its functionality. The GMC does everything the Remootio 3 does except for the following:

- Has
    - Gate Status
    - Party/Vacation Mode Selectors
    - Diagnostics
        - Battery Voltage/Condition/Level
        - Power Source
        - DIP Switch State
        - Input Terminals
        - Force Setting
        - Hardware/Software
        - System Errors
        - System Type
- Doesn't Have
    - Apple Home/HomeKit
    - Hostname (for the nerds)

## Which app should I use?

It doesn't matter, they're both the same app. The Remootio app might get updates faster, although it's yet to be confirmed. The Remootio app also has an extra button that lets you transfer your gate to the Ghost Controls app, although you can't transfer the gate vice-versa.

## Websocket API

The API is identical to the normal API, so it should be compatible with any plugin made for other Remootio devices (ex. ronniepettersson/homebridge-remootio).

## Finding the MAC Address

The MAC address of the GMC is the first 12 digits of the serial number of the device. This can be found in settings under Network setup -> Bluetooth information or Internet.

You can also find it by opening a terminal and running `arp -a xxx.xxx.x.xxx` where xxx.xxx.x.xxx is the IP of your GMC device (can be found in settings under Network setup -> Wi-Fi). It'll be listed under physical address.
