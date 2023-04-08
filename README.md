# Industrial-IOT-Datalogger-4-Layer

Industrial IOT Datalogger board based on Atmega2560 and compatible with Arduino IDE. The board size is 10x10 mm. 
It contains:
- SMPS and LDO power supply (+5V & +3V3).
- Controlling an AC appliance.
- DC Motor Speed Controller (Maximum current 3A). 
- Reading 0-10 v Digital Output sensors.
- Reading (0 - 5v / 0 - 10v) Analog Output sensors.
- Reading (4 – 20 mA) sensor.
- Real-Time Clock (RTC).
- Bluetooth Low Energy (BLE 4.0).
- Industrial Wi-Fi Module (ATWINC1500).
- SD Card Interface.
- RS232 Interface.
- RS485 Interface.

Notes:
- The supply voltage is +12V DC.
- The Power Supply contains several protections [Reverse Voltage Protection - Transient Voltage Suppressor - Under Voltage Lockout - PTC].
- The board contains Isolation for the analog part.
- The ADC used in the (4 – 20 mA) sensor is a 16-Bit ADC.
- DC Motor Speed and AC appliances controllers are isolated from the controller with Optocouplers.
- Reading 0-10 v Digital Output sensors part is Isolated from the controller with Optocouplers.
- ESD and overvoltage protection for all digital and analog input terminals.
