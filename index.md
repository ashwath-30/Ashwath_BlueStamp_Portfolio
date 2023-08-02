# BlueStamp - The Air Quality Monitor
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Ashwath S | Northwood High School | Electronic Engineering | Incoming Sophmore

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone


<iframe width="676" height="380" src="https://www.youtube.com/embed/NjfxezMAle8" title="Ashwath S. Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
|                                                                                                                                                             |
The DHT11 and the MQ-135 air quality sensor are required for this first milestone video. A power connection with 5 volts and ground is necessary for these components. Connect the red wire to the positive rails at the breadboard's tail end to charge the column. Next, connect the green and yellow wires to the rows where the center pins of the DHT11 and MQ-135 are located. The negative railing at the breadboard's back end is where the ground wire is attached. The pins on each component's orange and blue wires should be connected. The red wire in the MQ-135 is linked from the analog input A0 in the controller board, and the third yellow wire in the DHT11 is connected from the digital 2 input in the R3 controller board to the DHT11's leftmost pin. The Adafruit DHT library was included to link the code to the parts. The code reads air quality from the MQ-135 input and temperature, humidity, and heat index from the DHT input. Although the air quality is not quite right now, it should improve as the project goes on.

# Schematics 
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

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| UNO R3 Controller Board | This is the "powerhouse" of my poject; contains the VCC and Ground power, as well as numerous ananlog and digital inputs that are nesscary for the OLED, DHT11, and the MQ135 | $16.99 | <a href="https://a.co/d/5OrLeQE/"> Link </a> |
| 830 Tie-Points Breadboard | Powers up the components, it's the area where you "work" in | $9.99 | <a href="https://a.co/d/5oY5jsG/"> Link </a> |
| Prototye Expansion Module | What the item is used for | $9.99 | <a href="https://a.co/d/0Te8LhG/"> Link </a> |
| DHT11 Temperature and Humidity Module| This items reads the temperature, humidity and heat index in the the given area and outputs it as a value | $7.99 | <a href="https://a.co/d/bO8Tz7F/"> Link </a> |
| MQ135 Air Quality Sensor | This component reads the gas level in the current area and outputs it as an analog value; below 181 is good, while above 181 is poor | $7.99 | <a href="https://a.co/d/14zhDB1/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
