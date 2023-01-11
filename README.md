
# [Unity Sensor Board](https://loopon.tech/products/unity-sensor)
This repository contains example code for the Unity sensor board.
Specs can be found at https://loopon.tech/products/unity-sensor

## Flashing the Unity board
To flash the Unity board, the ESP32 must be put in the correct boot mode:
1. Hold down the boot button
2. Press the reset button
3. Release the boot button

Once flashing has completed. Prese the reset button to restart in normal mode.

## Projects
### 1. [Blink](/Blink)
This project blinks LEDs on all GPIO ports.
### 2. [Bluetooth Keyboard](/BluetoothKeyboard)
This project will will connect as a Bluetooth keyboard and type a a few sentences.
### Windows Setup
1. Go to Settings -> Bluetooth & Devices -> Add device
2. Select Bluetooth
3. After the scan has completed, Unity Keyboard should appear. Click and add device
4. Open Notepad.exe and watch it type

### Android Setup
1. Go to Settings -> Device connection -> Pair new device
2. Select Unity Keyboard in the list
3. Open a notepad app and watch it type
### 3. [Rainbow](/Rainbow)
This project cycles through colours of the rainbow using the onboard RGB LED.
### 4. [Temperature, Humidity and Ambient Light](/TempHumLight)
This project prints the readings from the HDC1080 (temperature/humidity) and the BH1750 (light) sensors.
### 5. [WiFi Scanning](/WiFiScan)
This project will scan and print WiFi access points.
