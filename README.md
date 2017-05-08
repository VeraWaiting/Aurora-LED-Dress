# Aurora Dress

### Introduction

Aurora Dress is a fantastical dress on which 44 LEDs blink in different colors and patterns according to the different movements of the wearer. It is a combination of art and science, or design and technology, to stimulate inspirations, excite imaginations, and create dreamy interactive experiences for users.

An absolute orientation sensor attached to the dress is used to detect Euler angles, accelerations, angular velocities, and angular accelerations of the wearer in different directions. Then an Arduino Uno processes these data and controls the blinking of 44 RGB Smart neoPixel LEDs to create different patterns: rainbow-like aurora for staying static, theatre chasing for jumping, wiping for spinning, etc.

With the development of science and technology, wearable technology is becoming more and more popular. As are LED dresses. We have figured out many ways to make a dress blink, like sewing LEDs on to a dress, attaching fibre optics to a dress, even making cloth itself glow. But all of these existing LED dresses blink just by themselves and have no interaction with the wearer. I wanted to explore the relationship between humans and wearables, thus I designed this Smart Blinking Dress, which blinks in a more meaningful way by discovering and reflecting the wearer in every of his/her movements.


### Technology

- An BNO055 absolute orientation sensor is used to detect the movement of the wearer.
- 44 Adafruit Smart neoPixels are solded and sewed onto a dress. 
- New classes are written in Arduino to realize different patterns of the lights.

### Process

1. Sketch:

![led dress - sketch](https://cloud.githubusercontent.com/assets/23609156/23991460/b59e5536-09f6-11e7-823c-9412d0168fff.jpg)

2. Schematic:

![led dress - schemetic - 1](https://cloud.githubusercontent.com/assets/23609156/25797229/26a64536-3391-11e7-9e99-c477fc43e763.jpg)

3. Testing BNO055:

4. Design the pattern (positions NeoPixels on the dress):

5. Sewing NeoPixels onto a piece of cloth

6. Soldering wires to connect NeoPixels

7. Sewing the piece of cloth onto a dress

8. Programming

9. Sewing the BNO055 sensor, the Arduino Uno, and a power bank on the inside of the dress

### Photos & Videos


### Continuing

Time-lapse photography
Mass production?
