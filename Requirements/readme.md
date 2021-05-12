### HIGH LEVEL REQUIREMENTS ###

1)  Turning the sunroof on and off as per the user by pressing a pushbutton (when push button is pressed sunroof is open and when it is released the sunroof gets closed.)

2)	Turning on the wiper( using moisture sensor) and adjusting it as per the intensity of the rain using Potentiometer Sensor (By just rotating the handle on the dashboard or something of that sort so that the wiper speed can be controlled.) 

### LOW LEVEL REQUIREMENTS ###

1)	When the push button is pressed i.e. when the input is 1, the LED will glow indicating the sunroof is open.
When the push button released i.e. when the input is 0, the LED will not glow indicting the sunroof is closed.

2)	When the moisture sensor senses the water indicating the windshield is wet and wiper should turn ON, that is indicated by GREEN LED on the discovery board.
When the ADC value is from 0 to 1500, it will take the input as 0 and the wiper is at medium speed.
