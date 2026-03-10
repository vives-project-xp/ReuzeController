# ReuzeController
a repository for the renovation of the giant controller made in 2020-2021
. Authors: Degeest Bram, De Smet Xander.
. Renovation: 2026

## about
The giant controller is (like the name says) a giant controller. It is moddeld after the SNES controller from nintendo. 
It has 10 buttons and can be used via bluetooth. The buttons work with a IR sensor that detects button presses. Originaly the controller used a Nucleo board as it's microcontroller with a bluetooth module attacht. the buttons are made out of 3D printed parts. The rest of the controller is a wooden plate cut in the shape of a controller the sides are lasercut wooden parts that bend for smootness. 

## Renovations

### buttons
We reprinted the buttons because, the pevious printed parts were very badly printed wit rough edges. We remade the buttons in fusion 360. The buttons are now cleaner and smoother this improves the use because the buttons don't have rough edges that scrape the side of the buttons. For the D-pad we remade the button holder and the d-pad. The holder is now correctly printed with the mounds for the IR-sensors printed to the base (this was previously printed apart and glued to the base). The start and slect buttons are still the same as the original.

### electronics
The original controller used a nucleo board with an pcb with a bluetooth model connected to it. Since the code for this project was not documented and we couldn't find it anywhere nor distract it from the board. We decided to get rid of the nucleo and the Bluetooth module and recplate it with a ESP32-C3-DevkitC-02  with build in bluetooth. We did however reuse the pcb for the connections of the IR-sensors. 

