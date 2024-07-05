# Hexapod Robot
The hexapod is a six-legged robot that can be controlled to move in any direction. The six legs give it a dynamic and versatile range of motion. Mounted on the robot is a crane that I designed and built myself, which is capable is retrieving anything on the ground and carry it around.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Bani G | Gunn High School | Aerospace and Mechanical Engineering | Incoming Junior

<!--- **Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Modifications

<iframe width="560" height="315" src="https://www.youtube.com/embed/G1wfri5acvk?si=vUckQLzvb-4nGpFE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Description
-->

# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/G1wfri5acvk?si=vUckQLzvb-4nGpFE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my final milestone, I built the controller and finished the entire build. The controller works via a bluetooth module that is attached to both the robot and the controller. The Joystick sits on top of a potentiometer, which works by measuring the displacement of the knob from the center, and traslates it into servo motor turns. My next steps will be to add my modifications which include a battery mount as well as a crane. I plan to build a mount on top of the hexapod for the crane, as well as a new remote for the crane. I might combine the hexapod remote and the crane remote into one remote later.

# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/opUCqyP4YVc?si=gO0VVhvIhBX_aKKY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my second milestone, I finished the robot. For this, I uploaded the code to the arduino and calibrated the legs of the robot. Calibrating the robot was very time consuming as it took a lot of time to precicesly line up the legs where I needed them to be. To calibrate the hexapod, I used the Processing application. After some time, I eventually managed to finish and get the data saved to the arduino. However, I will need to recallibrate if I ever unscrew the legs of the robot and rescrew it back on. As of now, the only thing left to complete is the controller.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/rit9lxJYW2E?si=OV__sKkzZn4NqmJ_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my first milestone, I have assembled the body of the hexapod robot. This just means attatching all the body parts to each other and wiring the robot. The only issue I had with my first milestone was the screwing of the screws as they were self tapping screws so they took more time and effort to screw in than normal screws. Also, I soon learned that attention to detail was important; I initially paid no attention to the orientation of certain plates, and later realized that they were meant to be flipped in the other direction. This led to tedious unscrewing and rescrewing of multiple mistakes. Another issue I had was screwing some plates on over the wires. I ended up having to unwire the robot and then screw the plates on, and then rewire under the plates.
My next steps are to build the controller and calibrate the robot. Then I will work on the software. Once this is complete I will be finished with the hexapod and will begin working on my modifications. I plan to make a crane for the robot and decorate it with LEDs to make it look pretty because right now it does not look pretty. I will explore my ideas for modifications more in depth once I finish the hexapod.

<!-- # Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->
# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Hexapod Robot Kit | The kit to build the base hexapod robot | $126.65 |https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"](https://www.amazon.com/Freenove-Raspberry-Crawling-Detailed-Tutorial/dp/B07FLVZ2DN?ref_=ast_sto_dp&th=1>|

<!--
| Servo motor | This is used to turn the turntable and change the direction of the crane | $16.99 | https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link](https://www.amazon.com/Control-Angle180-Digital-Torque-Helicopter/dp/B07NQJ1VZ2/ref=sr_1_7?crid=2P7XEAR23X8Y2&dib=eyJ2IjoiMSJ9.hAh-u35TYJocDYNVHDocFkgQum7rtTVfP8UrtXiv9HT6CQcsd8JG54KrHJ0PFrDmVH27JpBjudVApsoW2gdXjSI_QEa01K8rhf1WlwgMHkoF5_6J8TeJBck29VsSCcEWm2fycaCllVZvkA7utABpiot_ZsRu_lsiXpsDQ9unk64uNRhWVJzdQBz3p2J7xejTBCS1OYkmWshhV97WVTTbqIFcd5Vup8tsvOsAq3b-uj8ZSRzeXlP0_dedna4lbLCW1kGOyoNjXlGJ0D_qZJfrGj76F9c4pEqpgxZn8syg5xU.nQ9pXFDHfpbycIzCAnxOFjNGtdvVrGThlc6YoO-HTjI&dib_tag=se&keywords=servo+motor&qid=1720207073&sprefix=servo+%2Caps%2C141&sr=8-7)|
| Mini Servo | This is to move the crane up and down | $5.69 | <a [href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/">](https://www.amazon.com/Compatible-Helicopter-Airplane-Control-Accessories/dp/B0D1BY4SD6/ref=asc_df_B0D1BY4SD6/?tag=hyprod-20&linkCode=df0&hvadid=692875362841&hvpos=&hvnetw=g&hvrand=9754120160964201636&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-2281435178378&psc=1&mcid=91dd7dfb44a53e19a7a89baef4150607&hvocijid=9754120160964201636-B0D1BY4SD6-&hvexpln=73&gad_source=1) Link </a> |

-->
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |


# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/oBlrQPlmvdY?si=uAyb_n-3glpYcsWq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my starter project, I made the Weevil Eyes project. This is a small bug-like object whos eyes glow when it is dark. There is a light sensor which, when it doesn't detect any light, sends a signal to thie leds to light up. This project was very solder heavy and I got a lot of practice painstakingly soldering connections. I had trouble soldering the battery holder on, and therefore I had a lot of issues with the project before I finally managed to solder it properly and get it to work.
