RC Car

High school project developed in 2016 for an electronics fair with other schools.

When I was a kid I was really interested in how things worked. This curiosity along with my passion for remote control cars guided me into creating my own rc cars with my basic knowledge in electronics and components back then.

First I tried infrared communication. It was fun to understand how IR worked using a normal IR LED and a photodiode polarized inversely to get the signal from the emitter. 

(photo of basic circuit with IR LED and photodiode)

This solution was simple, but in practice it presents a lot of problems. The main one was the transmission distance. With a conservative polarization it reaches 5 to 8 meters, but when I try to increase that amount by leveling up the reverse current in the transistor base excitation circuit the car becomes unstable and uncontrollable because of the noise of solar light during the day. So now the car was only usable at night. Additionally, the emitter just sent one instruction for the car, and that was just to go straight. That sounds a little boring, but hey, it was my first electronic product, a simple design with my limited understanding of this whole world of electronics. By the way, the electrical noise that the motor induced in the circuit causes a lot of problems as well and the car just runs out of battery in a matter of minutes. 

After that first experience I decided to study a little bit more about how to improve my design and make a better car. With that motivation finally I ended up using a universal transmitter from a TV control and a phototransistor with 38kHz filter to demodulate the signal. That was a big improvement in the design, allowing more commands through a long distance. That was definitely a lot more funny than the previous versions.

(Photo of phototransistor IR circuit)

But in 2016 I started to formally study electronics at my school, and then I learned about microcontrollers and a bunch of different components, and now understand a little bit more about how they work and how you can use them in a circuit. With that in mind, I propose this… 

(Photo on final design)
