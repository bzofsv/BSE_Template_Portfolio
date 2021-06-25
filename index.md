# 32 x 8 LED Matrix Spectrum Analyzer
This project is an LED Matrix Spectrum Analyzer using Arduino and a 32 x 8 NeoPixel LED Matrix. It uses an FFT analyzer to convert audio input to numbers to be displayed on the matrix. It takes computer audio and displays the spectrum onto the LED Matrix. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Brandon Zhang | Lynbrook High School | Electrical Engineering | Incoming Sophmore

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone is getting the basic project working with my microphone input. I used an FFT analyzer on Processing to convert the input sounds into numbers representing the heights of each of the columns on the matrix. In Processing, I converted the number output of the FFt analyzer to numbers 1-8, representing the height of the columns in the matrix. One problem I ran into was that Processing did not have permissions to take audio input from my computer, but Processing was not asking for permissions at all, so I was not able to give it microphone access. I worked around this issue by restarting Processing and writing a code that would require a microphone, which caused Processing to ask for microphone access. 

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}
# First Milestone
  
My first milestone is getting the LED Matrix to light up in a snaking pattern all throughout the matrix. I used the Arduino with the NeoPixel LED Matrix library to write code to do this. This helped me familiarize myself with the NeoPixel Matrix code and the Arduino IDE, and allowed me to experiment with the coding process and how everything was wired together.

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone"){:target="_blank" rel="noopener"}
