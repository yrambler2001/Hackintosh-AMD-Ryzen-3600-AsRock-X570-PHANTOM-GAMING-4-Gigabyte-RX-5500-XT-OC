# Hackintosh-AMD-Ryzen-3600-AsRock-X570-PHANTOM-GAMING-4-Gigabyte-RX-5500-XT-OC
Big Sur (Catalina is on 'catalina' branch)
# Info PC

```
MB: AsRock X570 PHANTOM GAMING 4 $190
CPU: AMD Ryzen 3600 $210
VGA: Gigabyte RX 5500 XT OC 8GB $250
RAM: 32GB HyperX DDR4 16GB+16GB 3600Mhz FURY Black $210
SSD: Samsung 860 EVO 1TB $180
SSD: Samsung 860 EVO 500GB
Bluetooth: Asus USB-BT400 $15
Case: Deepcool KENDOMEN RD $60
PSU: Chieftec BDF-600S 600W $60
Cooler: DeepCool GAMMAXX 300 $20
```

# Hackintosh + OpenCore (Supported version: 0.6.3)

- https://dortania.github.io/OpenCore-Desktop-Guide

# Works

- Audio
- Ethernet
- Bluetooth
- GPU
- All USB ports
- Switch between Windows and MacOS with [rEFInd bootloader](https://github.com/agners/rEFInd) [(website)](https://www.rodsbooks.com/refind/) using mouse (configure boot order using EasyUEFI)

# Result

![Info](/images/info.png)
Geekbench 5 https://browser.geekbench.com/v5/cpu/4920819
Geekbench 5 Metal https://browser.geekbench.com/v5/compute/1906257
Geekbench 5 OpenCL https://browser.geekbench.com/v5/compute/1906247

# Note

The file config.plist. Please change MLB, SystemSerialNumber, SystemUUID into your code

```
<dict>
		<key>AdviseWindows</key>
		<false/>
		<key>SystemMemoryStatus</key>
		<string>Auto</string>
		<key>MLB</key>
		<string>xxxxxxxxxxxxxxx</string>
		<key>ProcessorType</key>
		<integer>0</integer>
		<key>ROM</key>
		<data>ESIzAAAA</data>
		<key>SpoofVendor</key>
		<true/>
		<key>SystemProductName</key>
		<string>MacPro7,1</string>
		<key>SystemSerialNumber</key>
		<string>xxxxxxxxxxx</string>
		<key>SystemUUID</key>
		<string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```
