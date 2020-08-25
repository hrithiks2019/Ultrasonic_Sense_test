# Ultrasonic Sensor Based Alarm


## Installation

Install the Arduino on to Your Computer
```
Arduino_link : https://www.arduino.cc/download_handler.php?f=/arduino-1.8.13-windows.exe
```

## Usage

```bash
Step1: Install Arduino Software on to Your Computer By visiting the Above Link

Step2: Press Code Button and Press Download as Zip File 

Step3: Extract the Downloaded Folder 

Step4: Open the Firmware.ino file inside the Firmware Folder 

Step5: Flash the Code to the Arduino 

```

## Wiring Scheme:

````
1.SENSOR AND ARDUINO:

     Arduino Uno                   Ultrasonic Sensor


        PIN 2   <------------------>   TRIGGER PIN
        PIN 3   <------------------>   ECHO PIN
        5V      <------------------>   VCC
        GND     <------------------>   GND

2. BUZZER TO ARDUINO:
         
        ARDUINO                                 BUZZER            

         WHITE WIRE(OUT +ve)  <------------->   RED(+ve)
         GREEN WIRE(OUT -ve)  <------------->   BLACK(-ve)


````
## License
[MIT](https://choosealicense.com/licenses/mit/)
