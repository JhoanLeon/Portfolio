# WRISTBANDCARE

## Summary
- Undergraduate workshop course project in 2021 
- Portable device with Bluetooth and USB rechargable battery
- Quick prototype with modules integration
- Small 2-layer PCB with SMT and THT components

## Description
During my undergraduate studies in electronics engineering at the University, I learned a lot about a wide range of different topics. However, due to the accelerated pace and the amount of academic work I carried, the course projects had to be quick prototypes that were as functional as possible. This project is a clear example of this.

For a workshop course in my last year of university, I had to choose a problem to solve using an electronic device. The problem I chose was the health monitoring of people using wearable devices. During those years, wearables began to gain high popularity. The proposed device had to measure heart rate and some environmental variables, such as temperature, humidity, and solar radiation, to generate health recommendations for people based on their surroundings and their heart activity. All of the measurements and communication with the device had to be wireless through Bluetooth and powered by a USB rechargeable battery.

With that in mind, I designed an integration board for some pre-made modules that combined to meet all the specifications. The final design was a 68.71mm x 31.12mm PCB with two layers and a mix of passive SMT components with THT modules.

![alt text](pcb_design.JPG "Complete PCB design")

This simple PCB was the foundation of the device. In that particular project, the manufacturing recommendations and best practices for PCB design were not even considered because of the rush and the handmade nature of the project assembly. The final integration of modules involved some important components, such as:

- Microcontroller ATtiny176 on a Digispark board
- UV Ligth Sensor ML8511
- HTU21D for environmental temperature and humitidy
- MAX30100 for oximetry and heart rate monitor
- SPI flash memory of 16MBit W25Q16BVSSIG
- BLE module JDY-23 with a CC2541 chip inside
- And some more for power management

All of these components needed to fit into a wristband-sized device! But nothing that a soldering iron and a glue gun couldn't solve. I am still impressed by the magic one can create in a single night of work. Here's a glimpse of the internal PCB assembly:

![alt text](internal_assembly.jpg "Internal PCB assembly")

Clearly, for that academic project, we didn't have a product designer, but the final goal of creating a functional device was accomplished. We were able to send messages through Bluetooth with all variables measured and store back-up information inside the non-volatile flash memory. I clearly remember the tight constraint of code space that we had with that low-power microcontroller.

![alt text](final_device.jpg "Final device")

It was a pretty decent final device for a first-time quick prototype, packed with a lot of hardware in the form of pre-made modules and wireless communication. Looking back, this was an interesting project that provided real, practical knowledge about electronics product development.