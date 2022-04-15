# learning-to-code-documentation
Progress report on my daily commitment of learning to code


<h3> tl;dr > If you’re self-learning to code, find a way to learn the basics in a fun way. Then start building stuff you want and learn <ins>what is needed</ins> to do so. </h2>



This is the documentation of the process of me learning to build stuff on the internet. I had no knowledge of coding so I started from the very basics.
 
 
  <h2>First Steps. Having fun is required.</h2>
  
I started with [Processing](https://processing.org/), a Java-based framework. Processing is suitable for digital media creations. At first I started learning the basics (variables, functions, etc). I followed the tutorials from [fun programming](https://funprogramming.org/) which is well made and easy to follow along. First few weeks I was making simple drawings and mini-animations of basic shapes or text.

![Untitled design](https://user-images.githubusercontent.com/34453848/162248841-3ab4999d-0a3b-48d4-b6d2-bc1097651054.gif)


I also knew about [P5js](p5js.org/) which essentially is Processing using JavaScript. Problem was that I had to setup my own code editor, local servers and all that. Since learning to code is in itself complicated, I decided to stick with Processing. Download their editor, write code, press play, boom.

  
  <h2>Start building stuff.</h2>
  
After the first steps of learning how to code, the next step is to find good and suitable challenges. Building stuff is the way to learn.

Still on Processing I made few mini-games. The challenge making them was that in games things get complicated VERY fast. Since I didn’t know how to translate physics (bouncing, collision detection, etc) into code, I had to find the simplest ways to make it work. For collision detection, I thought that the simplest way to know if two objects collide is to check for pixel colours. For example if cyan is on top of black then the objects collide.

<img src="https://user-images.githubusercontent.com/34453848/163529269-6daa4f85-cebd-4daf-9bbe-f537b7e23fd6.gif" width="400">

<img src="https://user-images.githubusercontent.com/34453848/163529279-1ca267df-990d-46c0-bcda-e28734805c3f.gif" width="400">

Next, I finally jumped to P5js.

![Screenshot 2022-03-08 at 19-13-44 Screenshot](https://user-images.githubusercontent.com/34453848/162249675-0f76dba3-0390-409b-8120-603f35d73ea5.png)

At first, to get familiar, I did the same style of generative projects as I did with Processing. Next, I found the project [NAG](nag.iap.de) and it was the perfect project to replicate. So I did that. 

Art generator is a project that you can input words, and get an artistic picture. The way this happens is that it establishes a connection with [Unsplash](https://unsplash.com/) via their API. Search for the input words and randomly pick and fetch 4 images from the results. Then with some controlled randomness a new composition appears on-screen. For example the image above is the result of the query “ordered chaos”.  
There is room for a lot more on this project but I decided not to continue with it since the original is so much I better. Plus, I wanted to start learning about APIs.

Next project was a chrome extension that helps you meditate. It’s a mini-game that you chant to move the character (a brain) to a certain point on screen. (add photo)

  
  <h2>Why and how</h2>
  
I really think when first learning to code, having immediate visual feedback of what is that you are building, is extremely beneficial. My desire to learn to code was about building tools that are useful. That is chrome extensions, simple solutions to  complicated services (see twitter post scheduler/manager). But, since I also have this artistic desire to create visual and auditory things, P5js is an amazing tool to learn.

My Muay Thai Teacher has a very simple and effective approach on teaching. “Learn and master the basics. If you do, you’re unstoppable.” OK he did not say unstoppable but the point is that if you master the basics you can do your life’s work with just that. Also, IF you need/want to learn more complicated stuff, it will be much simpler to do so. So in coding, that is my main focus. To master the basics. After all, frameworks come and go. Thinking clearly, designing systems, problem solving, etc will always be in the center of coding.

In the beginning, the main strategy is to learn what is needed for the current project. Sometimes overshoot for more advanced stuff. If it sticks, keep doing more. If not, fall back.

  
  <h2>HTML, CSS, Javascript & APIs</h2>
  
The third month I decided to start building browser applications. Hello HTML, CSS. Not much to say here, from the beginning I can see that “nobody likes you CSS” :D 

At first, I created a simple landing page about me. Then… a to-do list. (add picture of todo list)
Then, I wanted to store data so I can use my to-do list in everyday life. I found about localServer. Cool, but what about saving data remotely so I can access them from different instances (laptop, mobile, etc). I know that databases get complicated really fast so I wanted a simpler solution. How about storing my data to Google Sheets, GitHub, Notion? I can see all the security issues and all that but keep in mind these are learning experiments. I went with Google Sheets since I want to get familiar with their API. Hello, NodeJS.

  <h2>Three months later</h2>
So the three month period is over. The goal was to have the todo list completed by now. It’s almost there, I was able to make it read and write data from a dedicated Google Sheet but I wasn’t able to make it delete tasks. The end of the month has arrived and the app is not complete. I’m a little disappointed but it is what it is. I spent a whole week just for the Google API interaction. Since time is up, I decided to pause this project.

My brother is an artist and we decided he needs a portfolio website. So my next project is that. The learning objective is to get more familiar with HTML, CSS, vanillaJS, and deploying. 

For the next month my projects are 1) brother’s portfolio, 2) personal website, 3) Lorem Descriptium (a fun project I will link later). I will also make two blog post about the way I searched and learned about the things I needed to learn. I've found that almost all people when teaching they start doing stuff and explain as they go. But I believe the proper way is to give a map of what the finished project is, and start building on top of that. That way people learning already have an idea of what is needed.

  
  <h2>Conclusion</h2>
  
All in all, I’m doing progress faster than I expected. I have no delusions that I’m already a coding Jedi (gotcha [Dunning-Kruger effect](https://www.google.com/search?client=firefox-b-d&q=Dunning-Kruger+effect)) but progress is made and the streak of daily coding is not broken. I’m pleased.

  <h2>P.S.</h2>
When looking to learn a new tool, start with the information created by the people that made the tool. That is documentation, tutorials, their YouTube channel. And then look for tutorials from other people. Not the other way around.




<h4>links in article:</h4>
[Duck Duck Go](https://duckduckgo.com)<br>
[fun programming](https://funprogramming.org/)<br>
[Processing](https://processing.org/)<br>
[P5js](p5js.org/)<br>
[NAG](nag.iap.de)<br>
[Unsplash](https://unsplash.com/)<br>
[Dunning-Kruger effect](https://www.google.com/search?client=firefox-b-d&q=Dunning-Kruger+effect)
