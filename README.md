

* **Contributors:** CodingL (`@CodingFactoryL12`) und Tim (`@timbslr`)


* **Bill of Materials (`boom/boom.txt`):** ESP32, WS2812B LED Strip, Temperatursensor, Lichtsensor, Bewegungssensor, USB-C Breakout Board und LED Segment Display


* **3D-Druck-Dateien (`3d printing files/`):** `Back_Plate.stl`, `Light_Seperator.stl`, `body.stl`

* **Montage-Bilder & Code (`assembly/`, `files/Word_Clock_ESP_32`):** Fotos/Videos vom Löten, Lichttrenner und fertigen Aufbau



Hier ist ein passender, klar strukturierter `README.md`-Entwurf auf **Englisch**, komplett **ohne Emojis/Symbole**, der beide Mitwirkende erwähnt und genau zu deinen Dateien passt:

---

# ESP-Word-Clock

A custom real-life German Word Clock project built with an ESP32 microcontroller, 3D-printed parts, and integrated sensors.

Special thanks to @timbslr for the idea and original parts used in this project.

---

## Hardware Requirements

Below is the list of components used in this build:

* Microcontroller: ESP32
* LEDs: WS2812B LED Strip
* Display Supplement: LED Segment Display
* Sensors:
* Temperature sensor
* Light sensor
* Motion sensor (PIR)


* Power & Connectivity: USB-C breakout board
* Wiring & Soldering equipment

---

## 3D Printing Files

The required STL models for 3D printing can be found in the `3d printing files` directory:

* `body.stl` - Main clock enclosure
* `Light_Seperator.stl` - Grid divider to isolate LED light per letter
* `Back_Plate.stl` - Back cover plate for mounting and protection

---

## Assembly and Setup

1. 3D Print Parts:
Print `body.stl`, `Light_Seperator.stl`, and `Back_Plate.stl`.
2. Wiring & Soldering:
Assemble the WS2812B LED strip inside the light separator matrix. Connect the ESP32, USB-C breakout board, segment display, and sensors (temperature, light, and motion) according to your circuit configuration.
Reference images and videos are available in the `assembly` folder.
3. Firmware Upload:
Upload the code provided in `files/Word_Clock_ESP_32` to your ESP32 using the Arduino IDE or PlatformIO.

---

## Contributors

* CodingL (@CodingFactoryL12)
* Tim (@timbslr)

---

## Contact & Support

If you have questions or need help with the build, follow the pictures in the `assembly` folder or contact: info@codingl.de
