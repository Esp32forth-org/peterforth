Make ESP32forth  TALK ! 
======================= 


1)  first install the  TALKIE library, from the Arduino LIBRARY MANAGER
see attached  "talkie-install-6.jpg" printscreen. 
![Alt text](https://github.com/Esp32forth-org/peterforth/blob/main/speaks/TALKIE-INSTALL-6.jpg?raw=true "1")

2) Copy the attached  userwords.h, into your ESP32forth folder in the Arduino IDE.

3) Compile and upload to your ESP32forth as usual

4) Electric part  you can  listen with an earphone plugged into ADC output 
of ESP32forth on PIN D25 
or use  an active speaker with MIKE input.  you can plug directly GND and D25.
or you can install a low pass filter with a 1K resistor and a 10mF cap. I tested
both and both worked well with my speakers.

5) When everything is plugged in , and Esp32forth starts fresh 
you can begin testing  from the forth command line  some of the new words

EMERGENCY   STOP  ONE TWO THREE  DANGER DANGER ....  

use  "WORDS" to find more, or  read  the  userwords.h  to see the whole vocabulary.

This is version #1  of   ESP32forth-Talkie  by PeterForth 
soon watch the video demo on my channel  : https://www.youtube.com/c/PeterForth
