#8X8 LED PASSIVE DOT MATRIX PROGRAMMING#
###Description
The objective of this project is to develop the circuitry and software required to build an 8-by-8 passive matrix by testing it with LEDs.

Below is a video of my 8x8 LED matrix;

 <a href="http://youtu.be/Y7XjMiFkt50"><img src="https://raw.github.com/niralfernando/8x8-LED-Dot-Matrix-Project/master/assets/LED8x8.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


###Materials and Equipment### * [454 Miniature 8x8 Red LED Matrix](http://www.adafruit.com/products/454#Tutorials) ([Data Sheet](http://www.adafruit.com/datasheets/BL-M07C881.PDF)) * Arduino Mega 2560 Microcontroller * JW-75 Male Jumper Wires * Ceramic Resistors (Through hall, 10 kΩ) * KS-350 Deluxe Breadboard Wiring Kit * JW-75 Jumper Wire


###Installation instructions
######_Hardware setup_

 
 Development methods are described here:

 * [Resource 1](http://playground.arduino.cc/Main/DirectDriveLEDMatrix) * [Resource 2](http://www.interactionlab.biz/v2/?p=176)  

NOTE: The wiring configuration in this diagram does not apply to every LED matrix. See the corresponding data sheet or determine the rows and columns by connecting anodes and cathodes with the pins of the LED matrix.

The most challenging part in this project is trying to synchronize the written code with the LED matrix pin configuration.

![Pin Configuration](https://raw.github.com/niralfernando/8x8-LED-Dot-Matrix-Project/master/assets/config.png)
 Column #    | Pin # in Arduino | 
------------ | -------------    |
1            | 6                | 
2            | 7                | 
3            | 11               |
4            | 15               |
5            | 12               |
6            | 2                |
7            | 3                |
8            | 9                |

 Row #       | Pin # in Arduino | 
------------ | -------------    |
1            | 14               | 
2            | 4                | 
3            | 16               |
4            | 5                |
5            | 10               |
6            | 17               |
7            | 8                |
8            | 13               |       



######_Software setup_ * Add the FrequencyTimer2 library. FrequencyTimer2, written by Jim Studt, lets you create a zero jitter frequency output, and run your own function on each period * FrequencyTimer2 library download link ([download the zip file](http://www.pjrc.com/teensy/td_libs_FrequencyTimer2.html)): * How to add a library(<http://arduino.cc/en/Guide/Libraries>)


###Contribution
Credits go to Arduino's content rich resources and [interactionlab](http://www.interactionlab.biz/v2/?p=176).

_Author: [Niral Fernando](http://www.eng.uwaterloo.ca/~mn2ferna/) (NANDRix)_

_Email : <niral.fernando@gmail.com>_

_Phone: 647-922-9265_
  
 
 