# Arduino-Piano
Using an arduino to simulate a real piano

How does it work?
This is my side project for grade 12 computer technolagy where I make a piano using arduino hardware and capacitive sensing. I am going to create eight identical circut paths that invole a send pin (pin 2) and a recieve pin (pins 3,4,5,6,7,8,9,10) connected together with a 520 ohm resistor and an additional wire extending from the recieve pin (refer to schematic for how it would look). The resistor values differ based on the users prefrence. I went with a lower value because I want direct touch to the sensor. If a user would want touch from 5cm, 10cm, etc.. then they would just have to increase the resistance value. The circut is completed when a person touches the wire extending from the recieve pin (body acts as ground). Each "note" is made of aluminum foil because aluminum is a great conducter and it allows for great precision. The piezo buzzer will sound at different frequencys depending on which note is touched (ex. low sound for leftmost note, high sound for rightmost note). 


Parts List (and cost):
- Wires (<$1)
- Arduino ($10)
- Resistors 1 Ohm (<$1)
- Speaker or Piezo (<$1)
- Aluminium Foil (<$1)
- Paper (<$1)
- Paper Clips (<$1)

Total Cost
Approximately $16


Real Life Applications:
The real life application of this project is to be able to make a project that will be able to make music and depending on the person, good music. 


Design:
- A piece of paper with expertly laid out strips of aluminum foil (piano keys)
- Under each note will be a copper wire attached to the circut board
- A speaker in order to play the tone of each note

Challanges Overcome:
- Finding a decent adhesive to make sure the wires stay put on the aluminium. Electrical Tape
- Finding a place to put each aluminum strip (piano key). I taped each aluminum strip to a paper base.

Things I Would Do Differently To Improve:
- Make the design more portable. At the current moment, it is very difficult to transport my piano anywhere from the computer. If I had more time I would make a case for the piano and add an external 5V power supply so I could carry it around seemlesly.
- Implement a MIDI device so I could play real piano notes when each aluminum strip is touched instead of a piezo trying to imitate the sound of a piano

Since video files are too large, I am linking my video demonstration to a seperate website. The link can be found below:
https://www.dropbox.com/s/j3x3e9xsv96auto/20181114_124332.mp4?dl=0
