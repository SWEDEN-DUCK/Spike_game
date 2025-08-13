# Spike_game
This is a small portable game console that you can take with you wherever you go. It easily fits in your pocket or bag.

The foundation of the game was created by ultramegabombasticfuze, but I have fixed bugs and other issues. 

 All the pictures and files you need can be found further down. I hope everyone likes the new version I have made, and if you do please show me some respect by hitting the thumbs up so that more people can find this project. =) 

 In the STL file, I have two of each part. One with holes and one without, so in case you want to fix your own without it already having holes, there is one without holes. 

 How to set up.
 
* Arduino UNO R3
OLED       Arduino UNO R3
-----      --------------
GND   --->   GND
VCC   --->   3.3V
SCL   --->   A5
SDA   --->   A4

Button          Arduino UNO R3
   ------          --------------
   One side  --->  Digital pin 3
   Other side -->  GND

  * ESP32 C3 MINI 
   OLED         Esp32 C3 MINI
   -----        -------------
   GND   --->   GND
   VCC   --->   3.3V
   SCL   --->   9
   SDA   --->   8

   Button          Esp32 C3 MINI
   ------          --------------
   One pin  --->  Digital pin 3
   Other pin -->  GND

 Things I have fixed: 

- Game speed 

- Sprites

- Collision 

- High score 

- See score after you have died 

- Works on an Esp32 C3 Mini

- Smoother visuals 

- Better spike placement 

- Delay so you can see your score in case you accidentally skip it. 

Link to ultramegabombasticfuze: $ https://projecthub.arduino.cc/ultramegabombasticfuze $ 
