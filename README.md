# Assignment2
Rube Goldberg Machine

Nick Severson

![profile pic](https://i.imgur.com/1u8UkL5.jpg)

In this project, I created a Rube Goldberg with 4 stages and 2 triggers. The 4 different stages are 
all color coded (red for the first, yellow for the second, green for the third, and blue last). The 
first stage has the starting ball fall through a trigger plane, causing the red pannel to rotate down
 allowing the ball to fall into the moving "basket". The bottom of the basket disapprears, causing 
 the ball to fall to the yellow ramp (stage 2), hitting the green capsule. The green capsule then 
 moves due to the kinetic energy from the ball and falls onto the "seesaw" (stage 3). The "seesaw" 
 then launches the blue cube (stage 4) into the finish line (text zone with a box collider to act as 
 another trigger). This final trigger changes the displayed text to show that the machine is finished.
 
 One problem I was stuck on for quite some time was getting the text to change from my FinalTrigger 
 script. The solution (which turned out to be very simple) came from using a TextMeshPro object rather 
 than a TextMeshProUGUI object.


Video Link:
