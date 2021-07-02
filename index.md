# 32 x 8 LED Matrix Spectrum Analyzer
This project is an LED Matrix Spectrum Analyzer using Arduino and a 32 x 8 NeoPixel LED Matrix. It uses an FFT analyzer to convert audio input to numbers to be displayed on the matrix. It takes computer audio and displays the spectrum onto the LED Matrix. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Brandon Zhang | Lynbrook High School | Electrical Engineering | Incoming Sophmore

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)
  
# Final Milestone
My final milestone is getting the computer sound inputted into the computer so that my LED Matrix can analyze computer sounds as well as microphone sounds. I also added a button to the project, wired from the Arduino to the breadboard, in order to toggle between computer and microphone sounds. Using the button, I can change between displaying my microphone sound and my computer sound using the button. The button input is taken into the Arduino, printed to the Serial monitor, and read the input through Processing. Using the numbers from the button, I can toggle the sound from microphone to computer and back. The way I originally had the button wired, it was very inconsistent, so I had to rewire the button using a pull up resistor instead of a pull down.

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone is getting the basic project working with my microphone input. I used an FFT analyzer on Processing to convert the input sounds into numbers representing the heights of each of the columns on the matrix. In Processing, I converted the number output of the FFt analyzer to numbers 1-8, representing the height of the columns in the matrix. One problem I ran into was that Processing did not have permission to take audio input from my computer, but Processing was not asking for permission at all, so I was not able to give it microphone access. I worked around this issue by restarting Processing and writing code that would require a microphone, which caused Processing to ask for microphone access. 

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}
# First Milestone
  
My first milestone is getting the LED Matrix to light up in a snaking pattern all throughout the matrix. I used the Arduino with the NeoPixel LED Matrix library to write code to do this. This helped me familiarize myself with the NeoPixel Matrix code and the Arduino IDE, and allowed me to experiment with the coding process and how everything was wired together.

[![First Milestone] <html><iframe width="2544" height="1169" src="https://www.youtube.com/embed/lD5OQyxPeas" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></html>
