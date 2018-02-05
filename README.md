Asteroid Alert
==================================


I basically made a webpage using an API from Nasa that would give data about the number of asteroids that are close to the Earth on any given date. The date could be in the future or in the past. However there is a range of dates for which the API has data.<br>
When the user types the date in the input box and presses the button, the canvas in the page will be populated by images of asteroids around an image of the Earth. The number of asteroids in the canvas corresponds to the number of asteroids that would be present on the date entered by the user. The image of the Earth would not move whereas the asteroids would go from one place to another on bouncing.

**Why I did?**

I was not sure about what I wanted to do for my second project so I was just going through some APIs and I found this one interesting. However, I still did not know in what way I could visualise my data. So I started going through some of the examples of P5 play on their website. I really liked the one where the circles were bouncing against each other.

**How I did it?**
The first thing that I did was that I set up the AJAX call in a function. I then placed this function inside the click so that based on what the user inputs the function is called. Then based on what data I get from the API the data is used to create the number of asteroids. The image of the Earth will always be generated once whereas the number of asteroids would depend on the user data. 

**Challenges**
The main challenge that I faced was with the generation of the animation. I wanted the animation to be generated only when the user had entered the date and the API had returned the data. For this to happen, I had to put an if statement in the draw loop to make sure that the if statement is being checked again and again to see if the condition has been met and any data has been received. <br>
The problem was that once the data was received, the draw function would make the animation, However it would end up making new animations in every iteration. This would lead to creation of many asteroids at an increasing rate and after a few seconds the page would hang.

**Feedback**
The main feedback that I got was to make the webpage a bit more comprehensive. Apart from the animation of the asteroids, I could also make a click function, where once you click on an asteroid, a box will display relevant information of that asteroid such as the name, diameter, magnitude and whether or not the asteroid is potentially harmful/ harmless.

As the World Wide Web continues to grow and pervade our everyday lives, an ever-increasing amount of data and digital services are accessible to us via public web APIs—Application Programming Interfaces. Common to many web sites, including YouTube, Twitter, Google Maps, Wikipedia and more, these web APIs offer a way to programmatically request and re-purpose endless troves of information. 

How might we use these available resources to create unique, creative, and compelling web experiences of our own? 
Taking a hands-on approach, much of class time will be spent creating projects and writing code, primarily JavaScript, for client-side (front-end) web development.
