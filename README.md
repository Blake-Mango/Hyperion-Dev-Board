# Hyperion-Dev-Board

s a simple dev board that I made for Hack Club Blueprint. It has everything that I would want on a dev board—lots of GPIOs, plenty of grounds, and some other useful features (listed below). This was a fun and pretty easy project to make once I started to understand what I needed to do. It ended up being foundational to my ability to design PCBs, and it showed me how much I enjoy this kind of work. I hope I’ll be able to make even more dev boards later in life, and I’m definitely planning to try some other PCB ideas on Blueprint soon.


# Features
1. The RP2040 is the brain of this project handling all of the processing
2. this uses the W25Q16JVZPIQ with a whopping 16-Megabit flash menmory
3. Usbc this is just a normal USB-C Receptical to send data and also power 
4. one pin for 5v power and another pin for 3v power 
5. 9 pins for ground to make it easy to ground everything you need to 
6. this board comes wih 29 gpio pins 4 of which are dual use for analog inputs (ADC pins)
7. also on this board is an led to make it easy to check if the board is powered on od if there any any problems also to help debug or even program
8. and finaly a button to enter into BOOTSEL mode so you can program you board.

# schematic
<img width="1919" height="1075" alt="image" src="https://github.com/user-attachments/assets/a265dbae-f730-4497-a149-60fd5e9dbb2e" />

# PCB Layout
### Front:
<img width="846" height="357" alt="Screenshot 2025-12-07 113229" src="https://github.com/user-attachments/assets/ec3bb214-7c32-4ab3-bd43-af5acc2dae8b" />

### Back:
<img width="850" height="364" alt="Screenshot 2025-12-07 113249" src="https://github.com/user-attachments/assets/1cf70a8b-e8de-4e97-bdd8-667ff7c32f70" />

# Heres what it looks like when made
![top side dev](https://github.com/user-attachments/assets/2e0784a1-dec9-46b1-93c6-085d8b467fae)
![Bottom side dev](https://github.com/user-attachments/assets/438b3a9a-f014-4e25-9780-d13a18eeecd2)

# Demo
here is a short code that was made to just rotate the color of the onboard neopixel led

https://github.com/user-attachments/assets/beb6644e-a9f9-4d21-ad0d-ccec5cd91aba


