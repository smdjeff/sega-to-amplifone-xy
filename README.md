# sega-to-amplifone-vector
Sega G80 vector to Atari Amplifone adapter

* Converts Sega's vector outputs to Atari Amplifone levels and provides buffering.
* Input supply is +5V.
* The board makes +/-12v +/-9v and +0.5v on board.
* High quality TLE2082CP can be used to double bandwidth and slew vs older TL082 op-amps.
* Doubles voltage for X & Y to reduce stress on Sega XY game board amplifiers 
* Corrects black level and scale for RGB color signals

|     | Sega  | Atari |
| --- | ----- | ----- |
| X   | +/-4v | +/-8v |
| Y   | +/-3v | +/-6v |
| R   | 0-4v  | 1.0-3.5v |
| G   | 0-4v  | 1.0-3.5v |
| B   | 0-4v  | 1.0-3.5v |

![Image](docs/image0.png)
![Image](docs/image1.png)
![Image](docs/image2.png)

