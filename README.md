## Arduino project to change the I2C address  
1. Use the EchoMAV TF Luna Adapter to connect a Benewake TF Luna to the Arduino Uno.

Wiring:  
| Arduino UNO | TF-Luna Adapter |
|-----|-----|
| SDA | SDA |
| SDA | SDA |
| +5V | +5V |
| GND | GND |


1. Open the project in the Arduino IDE.
2. Plug in the Arduino Uno USB cable, in the IDE, set Tools > Port to the identified port
3. Set the board type (Tools > Board) to Arduino Uno
4. Click the checkmark to compile
5. Open the serial monitor (Tools > Serial monitor), set the baud rate to 115200
6. Click the arrow to load the code
7. You should see output in the serial monitor, follow the instructions to find a device and/or change the I2C address. Note that the address is input in decimal, not hex.
