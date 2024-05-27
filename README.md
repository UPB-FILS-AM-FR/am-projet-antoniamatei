# Mini-Game with a Ball

| | |
|-|-|
|`Author` | Matei Maria Ioana Antonia 

## Components of the crawler robot:
1x Raspberry Pi Pico RP2040 
2x Breadboard
2x Buttons
1x OLED 0.96 inch 128x64 SSD1306
Cables

## I developed a mini-game featuring a bouncing ball for the Raspberry Pi Pico, a compact and cost-effective microcontroller board. In this game, players control a paddle to keep the ball in play, aiming to prevent it from falling off the screen. The game is displayed on a small LCD screen connected to the Pico, with the paddle controlled via physical buttons or a joystick. The objective is to achieve the highest score possible by continuously bouncing the ball off the paddle. The game includes elements such as increasing difficulty, with the ball accelerating over time, and visual feedback for scoring and game over scenarios. The simplicity of the game makes it easy to understand and play, yet challenging enough to keep players engaged.

The motivation behind creating this mini-game for the Raspberry Pi Pico was to explore the capabilities of this versatile microcontroller and to learn more about embedded systems and game development. By developing a simple yet engaging game, I aimed to combine my interest in electronics with software programming, providing a practical and enjoyable project. This project allowed me to deepen my understanding of hardware-software integration, real-time processing, and user interface design. Additionally, it serves as an educational tool for demonstrating the potential of the Raspberry Pi Pico in interactive applications. The project also exemplifies how low-cost hardware can be used to create fun and interactive experiences, making technology accessible and enjoyable for a wide audience.

## Architecture

### Block diagram

<!-- Make sure the path to the picture is correct -->
![Block Diagram](schematics/block_diagram.png)

### Schematic

![Schematic](schematics/kicad_schematic.png)

### Components


<!-- This is just an example, fill in with your actual components -->

| Device | Usage | Price |
|--------|--------|-------|
| Raspberry Pi Pico RP2040 | Microprocesor | [31,69 RON] (https://www.sigmanortec.ro/placa-dezvoltare-compatibila-pi-pico-raspberry-rp2040-16mb-flash-type-c-cortex-m0?gad_source=1&gclid=EAIaIQobChMImKiNzLmthgMVZYyDBx1Q7QrPEAQYAyABEgKtGvD_BwE) |
| Breadboard | Breadboard | [12 RON](https://www.sigmanortec.ro/Breadboard-400-puncte-p129872825?gad_source=1&gclid=EAIaIQobChMInp6037mthgMVx5KDBx0whwwSEAQYASABEgIZtfD_BwE) |
| Buttons | Buttons | [12,45 RON] (https://ro.farnell.com/seeed-studio/111020103/button-module-arduino-raspberry/dp/4007869?gross_price=true&CMP=KNC-GRO-GEN-SHOPPING-PMax_Test_840_Lowmargin&mckv=_dc%7Cpcrid%7C%7Cplid%7C%7Ckword%7C%7Cmatch%7C%7Cslid%7C%7Cproduct%7C4007869%7Cpgrid%7C%7Cptaid%7C%7C&gad_source=1&gclid=EAIaIQobChMIvNja_rmthgMVcpSDBx14OQT_EAQYAyABEgKa__D_BwE) |
| Wires | Connecting components | [9.52 RON](https://www.sigmanortec.ro/40-Fire-Dupont-20cm-Tata-Tata-p210851325?gad_source=1&gclid=EAIaIQobChMIyd6wnrqthgMVb6ODBx0HogHOEAQYASABEgKmC_D_BwE) |

### Libraries

<!-- This is just an example, fill in the table with your actual components -->

| Library | Description | Usage |
|---------|-------------|-------|
| [lib-name1](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |
| [lib-name2](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |

## Log

<!-- write every week your progress here -->

In prima saptamana am vrut sa fac proiectul cu un robot pe senile, am facut schema pieselor si metoda de amplasare, insa am avut probleme la livrarea pieselor. 
Ulterior m-am gandit sa fac un joc de tetris unde am avut nevoie de urmatoarele piese: 
1x Raspberry Pi Pico RP2040 
2x Breadboard
2x Butoane
1x OLED 0.96 inch 128x64 SSD1306
Cabluri
Pe toate le am achizitionat de pe cleste.ro si sigmanortec. 

https://www.youmaketech.com/raspberry-pi-pico-retrogaming-system/ 
M-am folosit de link ul de mai sus pentru a asambla piesele, ulterior am scris codul

## Reference links

<!-- Fill in with appropriate links and link titles -->

[Tutorial 1]([https://www.youtube.com/watch?v=wdgULBpRoXk&t=1s&ab_channel=BenEater](https://www.youmaketech.com/raspberry-pi-pico-retrogaming-system/ 
)

[Article 1](https://www.explainthatstuff.com/induction-motors.html)

[Link title](https://projecthub.arduino.cc/)
