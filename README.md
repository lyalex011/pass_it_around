# Pass_it_around project

Welcome to the Countdown Express App, a project developed as part of Per Scholas Bootcamp. In this assignment, we dived into the fundamentals of Express.js by building a fun and interactive web application that simulates a countdown of bottles of your favorite beverage. 

### What We Achieved
In this project, we successfully achieved the following objectives:

Express Server Setup: We began by creating a new directory named "pass-it-around" and initializing a Node.js project using npm init -y. This laid the foundation for our Express application.

## Home Page (GET "/"):

We set up a basic Express route for the home page (GET "/") to display the initial message: "99 Bottles of [Your Beverage] on the Wall".
We included a link labeled "Take one down, pass it around" that directed users to the URL "/98", representing one less bottle.
Number of Bottles Page (GET "/:number_of_bottles"):

We extended our application by creating a route that dynamically handles the number of bottles in the URL parameter.
Each dynamic page displayed the number of bottles in the format "[number] Bottles of [Your Beverage] on the Wall."
We provided a link labeled "Take one down, pass it around" with a href set to the current number of bottles minus one.
To ensure a seamless experience, we excluded the "Take one down" link when no bottles were left.
Additionally, we added a link to start over, allowing users to return to the home page.

## Bonus Feature
As an extra touch of creativity, we added a bonus feature to our application. We transformed the text to create a quirky and engaging experience:
"99 little bugs in the code
99 little bugs
Take one down
Patch it around
127 bugs in the code"

Furthermore, we went beyond the initial requirements and incorporated an element of surprise by allowing the bug count to randomly increase as well as decrease. 
