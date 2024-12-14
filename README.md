# Smart-Parking-System-Using-ESP32
Here's information about creating smart parking system using ESP32.
Components needed:
1)ESP32
2)Servo motor
3)LCD display
4)Ultrasonic sensor
5)IR sensor
6)Jumper wires
7)Breadboard
All components are needed as per project.
If project has two gate(Entry and Exit) then two servo motor and ultrasonic sensors are required.
ideally 4 IR sensors required for parking slots.

connections:
ultrasonic sensor-trig pin-d5
           echo pin-d18
servo motor-d4
IR Sensor 1-d13
          2-d14
          3-d27
          4-d26
LCD display-SDA-d21
            SCL-d22
for vcc and gnd pin make a vcc and gnd rail on breadboard.
how to create rail on breadboard?
you can see red and blue lines on breadbord use red(+)line as vcc.
connect a wire with vcc pin on esp32 and connect second terminal to breadboard same for gnd pin, but connect gnd pin in blue(-)line.

How to change sensitivity of a IR srnsor and lcd display?
You can see a blue box on IR sensor or lcd display in tha box move the screw to change sensitivity of  IR sensor or lcd display. 
advantages of smart parking system:
1) driver can find parking spaces easily.
2) fuel effective and time effective.
3) if you can make it more smart than driver can pay the parking fees on the gate using barcode.







