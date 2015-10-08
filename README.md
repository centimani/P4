Project 4 Optimization
Creator Matthew Barker

Open Index.html will lead you to the main page of the website. For this page I inlined some CSS, compressed some Images, and anysnc'd some Javascript. 
My PageSpeed Insights scores were 95 mobile/94 desktop. 

To access the Pizza page that was used for the Framerate and Computation Efficiency, you can either open the link at the bottom of index.html (Cameron's Pizzeria). 
For the pizza page, I modified the main.js file. The three big fucntions I focused on was the updatePosition, resizePizzas, and the DOMcontentloaded event. 
Largely what was done for these functions was moving static variables outside of loops, reducing the layout calls, and saving static variables to decrease computing time for loops. 
At the time of writing, the average scroll speed time to generate the last ten frames was between .19-.30ms and the average time to resize pizzas was .66ms. 