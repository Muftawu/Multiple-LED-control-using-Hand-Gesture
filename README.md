# Multiple-LED-control-using-Hand-Gesture

                      GESTURE CONTROLLED LEDs

INTRODUCTION
Hello Guys, Welcome to my channel. In this project, we are going to control multiple LEDs with hand(finger) gestures using Python and Arduino. 
Stay tuned and enjoy. 

PREREQUISITES
First and foremost since we are going to be tracking our hands or fingers for that matter, we will a webcam.
A logitech webcam or ones installed on PC/laptops will easily do the trick. 

LIBRARY INSTALLATION
For this, we will need a special library called cvzone, which comes with the module for hand tracking. 
Another library required is the openCV library which gives us access to launch the webcam. 

HOW IT WORKS
Each finger is corresponded to a unique number and that unique number is in turn corresponded to a pinMode of an LED. 
So whenever the program detects that a finger is raised, a high value(3.3-5V) is sent to the pin number of the LED it corresponds to. 
As such giving it a potential enough to turn it on. This applies to all the other four LEDs used in this project. 

FINGERS AND CORRESPONDING LED PIN MODES

1. Index finger                                           -Red LED               -Pin 1

2. Index and Middle fingers                               -Blue LED              -Pin  2

3. Index, Middle and Ring fingers                          -Green LED           -Pin  3

4.  Index, Middle, Ring and little finger                  - Yellow LED         -Pin  4

5.  ALL fingers raised  - White LED                       - All LEDs go OFF




HARDWARE COMPONENTS REQUIRED 

1. Liquid Crystal Display (https://amzn.to/3mjTOEp)
2. Arduino Uno or any other compatible Arduino Board (https://amzn.to/3w2HZWA)
3. Breadboard (https://amzn.to/3vYcSLQ)
4. Jumper wires (https://amzn.to/3jNiSSG)
5. LED's ( https://amzn.to/3GwOcyB) 

 
