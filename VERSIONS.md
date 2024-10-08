* Infomation about versions found on devices and behaviours
   * you can get this information by telnet to device on port 2000
   * the version is show at connection

- EMWERK-JB201_V2-1.0.69, Gecko_OS-STANDARD-4.2.7-11064, WGM160P
    - https://github.com/JuiceRescue/juicepassproxy/issues/93
    - default configuration have a web console and telnet disabled, enabling telnet works but reverted automaticaly back to disabled

- EMWERK-JB201-1.0.46, Gecko_OS-STANDARD-4.2.7-11064, WGM160P
    - 3-phase 32A device, made in Mexico, 2022-07
    - send messages with version v09u
    - accepts setting offline and online current
    - revert to offline current afater around 5 minutes without server responding
    - The first device that was controlled locally https://github.com/JuiceRescue/juicepassproxy/pull/69
    - Known Issues
        - When charging Volvo XC40 the voltage drops from aroung 220 V to 139-140 V
            - This happen to more than one device, and does not happen when charging Bolt or BYD Yuan Plus             

- EMWERK-JB_1_1-1.4.0.28, 2021-04-27T20:39:50Z, ZentriOS-WZ-3.6.4.0
    - send messages with version v07
    - 2024-10 apparently does not support offline current configuration, after power cycle returns to the current rating

