## Adafruit TB6612 Motor Driver Breakout PCB

<a href="http://www.adafruit.com/products/2448"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit TB6612 Motor Driver Breakout. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/2448

### DESCRIPTION
Spin two DC motors, step one bi-polar or uni-polar stepper, or fire off two solenoids with 1.2A per channel using the TB6612. These are perhaps better known as "the drivers in our assembled Adafruit Motorshield or Motor HAT." We really like these dual H-bridges, so if you want to control motors without a shield or HAT these are easy to include on any solderless breadboard or perma-proto.

We solder on TB6612 onto a breakout board for you here, with a polarity protection FET on the motor voltage input and a pullup on the "standby" enable pin. Each breakout chip contains two full H-bridges (four half H-bridges). That means you can drive 2-4 solenoids (only two can be active at a time, on opposite bridges), two DC motors bi-directionally, or one stepper motor. Just make sure they're good for 1.2 Amp or less of current, since that's the limit of this chip. They do handle a peak of 3A but that's just for a short amount of time, like 20 milliseconds. What we like most about this particular driver is that it comes with built in kick-back diodes internally so you don't have to worry about the inductive kick damaging your project or driver!

There's two digital inputs per H-bridge (one for each half of the bridge) as well as a PWM input per driver so you can control motor speed. Runs at 2.7V-5V logic. The motor voltage is separate from the logic voltage. Good for motor voltages from 4.5V up to 13.5V! This wont work well for 3V motors.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit.com](https://www.adafruit.com)!

Creative Commons Attribution, Share-Alike license, check license.txt for more information All text above must be included in any redistribution - 
See license.txt for more information.
