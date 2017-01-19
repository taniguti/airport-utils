# airport-utils
Small scripts for wireless settings of macOS.

## SetPrimaryWirelessNetwork

Put the wireless networks top of the prefer network list.

    Usage: sudo ./SetPrimaryWirelessNetwork -w SSID_NAME [-s security_type]
    Options:
        -h  : Show this message.
        -s s: Security type of the wireless network (Optional)
        -w s: SSID aka Wireless network name

    Security type:
        OPEN for none
        WPA for WPA Personal
        WPA2 for WPA2 Personal
        WPA/WPA2 for WPA/WPA2 Personal (macOS 10.12 or later)
        WPAE for WPA Enterprise
        WPA2E for WPA2 Enterprise
        WPAE/WPA2E for WPA/WPA2 Enterprise (macOS 10.12 or later)
        WEP for plain WEP or for Password
        8021XWEP for 802.1X WEP
