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
