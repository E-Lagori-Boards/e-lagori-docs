+++++++
Arduino
+++++++

Prerequisites:
==============

Arduino IDE: 
    Download and install the latest version of the Arduino IDE from https://www.arduino.cc/en/software
    A compatible USB cable to connect your board to your computer.

Installation Steps
==================

1. Add Board Manager URLs

    - Open your Arduino IDE and go to File > Preferences.

    - Locate the Additional Board Manager URLs field.

    - Paste the following URLs, separated by commas if you have other URLs present:

    - ``https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json``

    - ``https://raw.githubusercontent.com/E-Lagori-Boards/e-lagori-docs/main/package_e-lagori.json``
    
    - Press the "OK" button to save changes.

2. Install Board Packages

    - Navigate to Tools > Board > Boards Manager.
    - Search for "E-Lagori" and install the package specifically for E-Lagori boards. Make sure you select the latest version available.

3. Select Your Board

    - Go to Tools > Board and scroll to the "E-Lagori Boards" section.
    - Choose E-Lagori D_ESP_WVR from the list of boards.

4. Select the Port

    - Connect your E-Lagori D_ESP_WVR board to your computer via the USB cable.
    - Go to Tools > Port and select the port where your board is connected. On Windows, it will typically be something like "COM3"; on macOS or Linux, it may look like "/dev/ttyUSB0".

**You're Ready to Go!**

You've successfully installed the E-Lagori D_ESP_WVR board in your Arduino IDE. Now try following these steps to confirm proper installation:

    1. Open the "BoardTest" example code in the Arduino IDE (File > Examples > D_ESP_WVR > BoardTest)
    2. Click the Upload button.

If the code uploads without errors and the Serial Monitor will show the Module details, the installation was successful!

Troubleshooting
===============
- If you encounter issues, double-check the URLs entered in the Boards Manager URLs field.
- Ensure your USB cable is functional and properly connected.
