# Home Automation using Particle and Amazon Echo


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Varun | Fremont High School | Engineering/Math/Coding | Incoming Sophomore

![Headstone Image](https://user-images.githubusercontent.com/107944435/176736426-d27e85cc-f735-488e-835c-b720ac0dfc0b.JPG)

 # Final Milestone 


My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

 [![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"} 

 # Second Milestone
 
 
My second milestone was the full completion of the base project without any modifications. First I figured out how particle worked, their CLI, their API, and everything else. Then I tried to figure out how to link particle to Alexa but I had no luck and couldn't figure it out at all. After a week of looking through all the forums and documents I could find I eventually gave up and looked at the example project again. I realized that the problem could be that I was coding eveything in the Alexa dev while the example coding was all through lambda. (I thought this was an outdated method since the Alexa dev creates a Lambda function itself automatically). I decided to switch after reading his code and realizing that I did not really know what was going on in the code. All the tutorials tell you to just copy paste the code so I eventually did that after understanding what the majority of the code does into lambda. After getting the AppID and all the authentication with particle setup I started making the circuit for LED's and a DHT22. The DHT22 orginially didn't work so I tried using it with arduino to troubleshoot and I figured out the sensor was wrong and ended up using a DHT11. The last thing to set up was the .ino file in particle which is pretty simple and add the DHT library. Note that the adafruit library for particle didn't work for me and I used the adafruit library that was made for arduino. Set up the intent schema and some custom slot types and everything should work.

[![Second Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1657838671/video_to_markdown/images/youtube--M-2lPy64P-0-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=M-2lPy64P-0 "Second Milestone")
# First Milestone
  

My first milestone was getting Alexa connected to Alexa Skills Kit (ASK) and getting them talking to each other. The tutorials and websites on this subject are very old and Alexa has changed a lot since then. There is a lot about connecting Lambda to ASK but Alexa does this automatically for you now so I didn't have to worry about that part anymore. You can now code everything directly from ASK so once I figured that out I started trying to link my Alexa dev account to my actual Alexa. The only way to connect to Alexa via a computer is to use Firefox so I switched my work to Firefox. As long as you use the same account for Alexa and the developer account they will automatically connect as a dev skill. I coded a test response in my skill referencing the hello world skill Alexa gives you which can be seen in the video. 

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1656604140/video_to_markdown/images/youtube--Fum1yOzwwfg-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=Fum1yOzwwfg "First Milestone")

# Starter Project - Useless machine
  

My starter project was building a Useless machine with the Spikenzie Labs kit. I had to solder resistors, switches, terminals and LEDs onto a printed circuit board. Then I connected the board to a motor. I attached the arm which would be used to turn the main switch off and screwed the entire thing inside a box. I placed a battery pack and connected the battery pack wires and the motor wires to the PCB. The arm initially missed the switch and was slightly offset so I shifted the arm a little and so that it would hit the switch. I then assembled the entire box around the PCB, motor, and battery pack.  I made sure everything worked and that's how I built my Useless Machine. 

[![Varun K Starter Project](https://res.cloudinary.com/marcomontalbano/image/upload/v1655914257/video_to_markdown/images/youtube--k8xlz6fg6z4-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=k8xlz6fg6z4 "Starter Project")
