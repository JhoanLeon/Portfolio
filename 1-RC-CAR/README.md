# RC CAR

## Summary
- High-school project in 2016 
- Remote Control Car with RF communication
- Old-school 8-bit PICs designs

## Description
My journey into electronics began when I was a child. I have always been very interested in knowing how things work and I still remember that science fair project when my father and I did a simple circuit with an alkaline battery a switch and a lamp to show how the electricity works. That was amazing for me in fourth or fifth grade (maybe).

Then in the school, sixth grade, I made a robot brush and I was more than excited seeing what a battery and a motor can do. After that years, my curiosity in this world of electricity and electronics grew and grew. 

I tried make a wind farm with some motors and leds, burning them up by not use any resistance. Tried a fail electric boat to play with friends but it ended up short-circuited at the bottom of my grandmother's tank. And on and on... Project after project I was discovering this beautiful world even trying to write a book in the high-school to consolidate all of my knowledge until then and help other students with the basics. A crazy thing for sure!.

This curiosity along with my passion for remote control cars (another interesting story) guided me into creating my own rc cars with my basic knowledge in electronics and components back then in 10th grade.

First I tried infrared communication with a transistor to control the motor. It was fun to understand how IR works using a normal IR LED and a photodiode polarized inversely to get the signal from the emitter.

(photo of basic circuit with IR LED and photodiode)

This solution was simple, but in practice it presents a lot of problems. The main one was the transmission distance. With a conservative polarization it reaches 5 to 8 meters, but when I try to increase that amount by leveling up the reverse current in the transistor base excitation circuit the car becomes unstable and uncontrollable because of the noise of solar light during the day. So now the car was only usable at night. Additionally, the emitter just sent one instruction to the car, and that was just to go straight. That sounds a little boring, but hey, that was my first own rc car. By the way, the electrical noise that the motor induced in the circuit causes a lot of problems as well and the car just runs out of battery in a matter of minutes.

(photo of my electronic set-up with my RGB flashing IR car)

After that first experience I decided to study a little bit more about how to improve my design and make a better car. With that motivation finally I ended up using a universal transmitter from a TV control and a phototransistor with 38kHz filter to demodulate the signal. That was a big improvement in the design along with the transistorized H-bridge for the motor control, allowing more commands through a long distance. That was definitely a lot more funny than the previous versions.

(Photo of phototransistor IR circuit)

In 2016 I started to formally study electronics at my high-school, and then I learned about microcontrollers and a bunch of different components, and now understand a little bit more about how they work and how you can use them in a circuit. With that in mind, I propose a brand-new version of the RC Car but this time with RF communication through a NRF24 chip, a microcontroller and a IC H-Bridge. I design the PCB for the Car and the Control, but unfortunately I don't take a lot of photos from that my first PCB design, I could only recover two blurry-photos from the unterminated schematics of both designs.

(Photo of both schematics)

Unfortunately, I don't have any photo of the final car, I even went to an inter-scholar fair of robotics at the end of 2016 to present my modern and very fast RC Car with RF communication. That car give me a lot of fun and even more knowledge about electronics and why this is my passion. It probably ended up in my personal graveyard of dismantled old toys and RC cars for recycling their components.

