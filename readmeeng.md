ReactLab Software Installation and User Guide

1. Introduction
    The ReactLab software has been developed to automate ASTM reactivity analysis using a Lutron TM-947SD thermometer, facilitating temperature recording from thermocouples during predefined time measurements. This guide provides step-by-step instructions on how to use the software and perform measurements efficiently.

2. System Requirements
    - Operating System: Windows 10 or later
    - Driver for USB to Serial DB9 (RS232) Converter:
        - Driver: TrendNet TU-S9
        - Download Link: (insert link here)
        - Internet Access (for driver download)

3. Installation and Initial Configuration
    3.1 Download Software
        - The ReactLab software is packaged as a single executable and can be found in the C:/ReactLab folder.

    3.2 Install USB to Serial Driver
        - Connect the USB to Serial converter to the computer.
        - Install the TrendNet TU-S9 driver.

    3.3 Configure Thermometer
        - Connect the Lutron TM-947SD thermometer via RS232 to USB cable.

    3.4 Configure COM Port
        1. Open Device Manager: Press Windows + X and select Device Manager.
        2. Expand Ports (COM & LPT).
        3. Find "USB to Serial Adapter (COMx)", where COMx is the automatically assigned port number.
        4. Right-click and select Properties.
        5. In Port Settings, click Advanced....
        6. Set COM Port Number to COM12.
        7. Click OK and restart the computer.

4. Starting the Program
    1. Navigate to the installation folder (C:/ReactLab).
    2. Double-click the executable file (ReactLab.exe).

5. Using the Program
    5.1 Select Analysis Duration
        - Choose analysis duration from available options.

    5.2 Enter Sample Codes
        - Enter sample codes for each active thermocouple.

    5.3 Prepare for Measurement
        - Insert sample into container and press Enter to start measurement.

    5.4 Export Results
        - Export data to file after measurement completion.

6. Troubleshooting Common Issues
    6.1 Serial Port Error
        - Problem: "Error opening serial port. Check connection."
        - Solution: Verify thermometer connection and COM port configuration.

    6.2 Screen Lockout
        - Problem: Screen locks after 15 minutes of inactivity.
        - Solution: Adjust system power settings or use software's automatic cursor movement feature.

Conclusion
    This guide should facilitate efficient use of the ReactLab software.

Additional Information
    For installation or software usage questions, contact Lhoist's IT support team.
