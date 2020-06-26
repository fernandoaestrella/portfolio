<div align="center"> <h1> Portfolio </h1> </div>

### Projects

---

[Skunworks Course Scheduler](https://github.com/brandeis-skunkworks/course-scheduling/tree/master/Vagrant)

My contributions:

I went through all beginning stages of the project, from ideation, to team building, to planning.

This state machine shows the different states the client needed the application to be in while scheduling.

<img src="images/scheduler-state-machine.jpg?raw=true"/>

I then lead the team to develop the front end pages displayed below.

<img src="images/schedulerA.png?raw=true"/>

<img src="images/schedulerB.png?raw=true"/>

<img src="images/scheduler-home.png?raw=true"/>

Due to the COVID-19 pandemic, many team members had to abruptly return back home. I am coding the Back End so that a Node.js server connects with the database and communicates with the Front End through a server running React, as shown in the following code:

[Front End communicating with Back End](https://github.com/brandeis-skunkworks/course-scheduling/blob/manual-scheduling-front-end/scheduling-app/src/App.js)

[Back End communicating with Front End](https://github.com/brandeis-skunkworks/course-scheduling/blob/manual-scheduling-front-end/api/app.js)

---

[Clef: A music learning website](https://github.com/jufer002/clef)

In a  team of 4, we created Clef in Ruby on Rabils. Clef is an online platform for people passionate about music and learning it. Users can create courses with sections and sections with lessons. They can upload videos or images to a lesson. They can also tag lessons, search for courses and lessons, autoscroll a lesson, and keep track of their progress in a course.

My contributions:

I focused mainly on search, progress report, autoscroll and the course display page (shown below).

<img src="images/clef.png?raw=true"/>

<img src="images/course-create.png?raw=true"/>

<img src="images/user-page.png?raw=true"/>

---

[Facebook Post Generator](https://github.com/fernandoaestrella/nlp-final-project)

Natural Language Processing project done in Python as a team where we applied Machine Learning to determine the sentiment a given article might carry and then created a possible response someone could have to it mixing a summary of the article, the sentiment, and some randomization.

My contributions:

Mainly adapted base sentiment analysis code to work with the possible input articles we would be receiving, among other tasks. Experimented with all models and features extracted and decided on the most effective one. Found here: [Testing diverse classifier models and feature extractors](https://github.com/fernandoaestrella/nlp-final-project/blob/master/all_together_e.py).

---
[RoboCup Agent in C Sharp](https://github.com/fernandoaestrella/RoboCup-Agent-in-CSharp)

Robocup 2D is a worlwide competition that pits teams of AI writers to create the brains of a simulated robotic agent playing soccer.

This was a proyect we started in college to practice UDP connections and AI. This one specifically is a client that only starts a connection with the server, starts a player, interprets the whole received string (only the "see" string), determines the position of the player with a simple method based on the closest flag and knowledge of its position, and with that information either moves to a desired position, waits for an amount of time determined by the user, and asks for another position, or closes in on the ball and kicks it to the goal (assuming they were both being seen). It is written in C Sharp.

My contributions:

Aproximately the later half of the code located here: [Program.cs](https://github.com/fernandoaestrella/RoboCup-Agent-in-CSharp/blob/master/RoboCup%20Agent/RoboCup%20Agent/Program.cs)

We did not create the graphical simulation shown below. It is used to visualize the behavior of the simulation.

<img src="images/robocup.jpg?raw=true"/>

---

### Games

---

[SlideIn](https://github.com/fernandoaestrella/SlideIn)

A game made in Unity in which the player summons units in a table top gameboard. The goal is to slide your units into the opponent's goal tile. You can also remove an opponent's unit by placing 3 of yours in front of it.

My contributions:

All code in C Sharp and Scene configuration written by me.

To play:

Go to [SlideIn.exe](https://github.com/fernandoaestrella/SlideIn/blob/master/SlideIn.exe), download and run it.

To see code:

Go to [Assets](https://github.com/fernandoaestrella/SlideIn/tree/master/Assets) and look at the C Sharp files.

<img src="images/slide-in-image.png?raw=true"/>

---
[Improved Pong](http://example.com/)

Some improvements made to a Pong-like game concept (single player Pong with high score count), like:
- Ability to shoot multiple shots
- Paddle freezes for some time when hitting the ball
- Paddle gets smaller after every hit
- Shot accelerates or slows ball depending on whether the ball was approaching or going away
- Score per time calculation
- Ball accelerates after hitting paddle
- Ball goes redder the faster it goes

---
