<div align="center"> <h1> Portfolio (90% complete)</h1> </div>

### Projects

---

[Skunworks Course Scheduler](https://github.com/brandeis-skunkworks/course-scheduling/tree/master/Vagrant) (Jan 2019 - Present)

[Brandeis Skunkworks](https://brandeisskunkworks.herokuapp.com) is a student organization focused on providing support, mentorship and experience to student groups interested in developing ideas that mainly improve the campus.

Course Scheduler is a React web application that will allow department coordinators to more easily schedule classes in pre-defined time slots while taking into account many diverse constraints set by professors and by the nature of the classes. The team had 7 members at its peak and has had 10 members over its lifetime.

My contributions:

I went through all stages of the project, from ideation to team building, to planning, and to execution.

This state machine shows the different states the client needed the application to be in while manually scheduling.

<img src="images/scheduler-state-machine.jpg?raw=true"/>

I then lead the team to develop the front end pages displayed below, and made the mockup for the first one. I set up and managed a Vagrant virtual environment that could be replicated in any machine, facilitating new members getting up to speed with the project and avoiding problems with the environment used to develop, later on. I also performed other managerial duties like give status of the project, find support, coordinate and attend continuous meetings with stakeholders, etc.

<img src="images/schedulerA.png?raw=true"/>

<img src="images/schedulerB.png?raw=true"/>

<img src="images/scheduler-home.png?raw=true"/>

Due to the COVID-19 pandemic, many team members had to abruptly return back home. I am coding the Back End so that a Node.js server connects with the database and communicates with the Front End through a server running React, as shown in the following code:

[Front End communicating with Back End](https://github.com/brandeis-skunkworks/course-scheduling/blob/manual-scheduling-front-end/scheduling-app/src/App.js)

[Back End communicating with Front End](https://github.com/brandeis-skunkworks/course-scheduling/blob/manual-scheduling-front-end/api/app.js)

---

[Clef: A Music Learning Website](https://github.com/jufer002/clef) (Spring of 2020)

In a  team of 4, we created Clef in Ruby on Rails. Clef is an online platform for people passionate about music and learning it. Users can create courses with sections and sections with lessons. They can upload videos or images to a lesson. They can also tag lessons, search for courses and lessons, autoscroll a lesson, and keep track of their progress in a course.

My contributions:

I focused mainly on search, progress report, autoscroll and the course display page (some shown below). Find it here: [Course viewer](https://github.com/jufer002/clef/blob/master/app/views/courses/_course_viewer.html.erb). I also gave suggestions on and created some UI features.

<img src="images/clef.png?raw=true"/>

<img src="images/user-page.png?raw=true"/>

---

[Facebook Post Generator](https://github.com/fernandoaestrella/nlp-final-project) (Fall of 2019)

Natural Language Processing project done in Python as a team of 3 where we applied Machine Learning to determine the sentiment a given article might carry and then created a possible response someone could have to it by mixing a summary of the article, the sentiment, and some randomization.

My contributions:

Mainly adapted base sentiment analysis code to work with the possible input articles we would be receiving, among other tasks. Experimented with all models and features extracted and decided on the most effective one. Found here: [Testing diverse classifier models and feature extractors](https://github.com/fernandoaestrella/nlp-final-project/blob/master/all_together_e.py).

---

[Low-Cost, Low-Weight Telepresence Device](https://www.dropbox.com/sh/hmedamt5jmw2cwx/AAAx05Mv4IYWZDVO-P1pUcCya?dl=0) (2015)

As part of the final project to opt for the title of Electronic Engineer, planned and built a low-cost, low-weight telepresence solution based on a Raspberry Pi, distance sensors, and Internet connection. 

<img src="images/3D design.png?raw=true"/>

<img src="images/final.png?raw=true"/>

<img src="images/telepresence-device-diagram.png?raw=true"/>

<img src="images/schematic.png?raw=true"/>

---

[RoboCup Agent in C Sharp](https://github.com/fernandoaestrella/RoboCup-Agent-in-CSharp) (2015)

[RoboCup Soccer](https://www.robocup.org/leagues/24) is a worlwide competition that pits teams of AI writers to create the brains of a simulated robotic agent playing soccer.

This was a proyect we started in college, in a group of 3, to practice UDP connections and AI. This one specifically is a client that only starts a connection with the server, starts a player, interprets the whole received string (only the "see" string), determines the position of the player with a simple method based on the closest flag and knowledge of its position, and with that information either moves to a desired position, waits for an amount of time determined by the user, and asks for another position, or closes in on the ball and kicks it to the goal (assuming they were both being seen). It is written in C Sharp.

My contributions:

Aproximately the later half of the code located here: [Program.cs](https://github.com/fernandoaestrella/RoboCup-Agent-in-CSharp/blob/master/RoboCup%20Agent/RoboCup%20Agent/Program.cs)

We did not create the graphical simulation shown below. It is used to visualize the behavior of the simulation.

<img src="images/robocup.jpg?raw=true"/>

---

[Electrocardiogram](https://github.com/fernandoaestrella/Electrocardiogram) (Fall of 2014)

As part of a team of 2, created an electrocardiogram display by picking up very small voltage differences in 3 extremities, amplifying them, filtering them, converting them to a digital value that an [EasyAVR](https://www.mikroe.com/easyavr) board (a development board based on the ATMEGA16A microcontroller) could understand, and serializing and sending through USB to a laptop with a [Processing](https://processing.org/) program displaying the variation of voltage in the heart and calculating and displaying the beats per minute.

My contributions:

Configured the ADC (Analog to Digital Converter) interface (shown [here](https://github.com/fernandoaestrella/Electrocardiogram/blob/master/Electrocardiogram/better%20res/procc.c)), configured the USART's (Universal Synchronous
Asynchronous Receiver Transmitter) serial transmission (shown [here](https://github.com/fernandoaestrella/Electrocardiogram/blob/master/Electrocardiogram/transmit%20heart%20pulse/transmit%20heart%20pulse/transmit%20heart%20pulse.c)), and produced the [Processing](https://processing.org/) display program (shown [here](https://github.com/fernandoaestrella/Electrocardiogram/blob/master/Electrocardiogram/graph_heart_rate/ultimo/graph_heart_rate_plus_BPM_display.pde)). 

Co-developed and co-produced the amplification and filtering external circuitry (it was not in the AVR board) as shown below. Chose a low pass filter of order 5 (to filter enough), with a Sallen-Key topology (ideal for using less components and using a unique power source) and Tschebyscheff classification in regards to its frequency response (because of its steep atenuation at the cutoff frequency, so that a 60 Hz frequency component, common in power lines, may be atenuated). Report [here](https://github.com/fernandoaestrella/Electrocardiogram/blob/master/Electrocardiogram/Reporte%20EKG.docx) (in Spanish).

<img src="images/low pass filter.png?raw=true"/>

---

[Motion Controlled RC Toy Car](https://github.com/fernandoaestrella/Motion-Controlled-RC-Car) (Spring of 2014)

As part of a team of 2, modified a cheap RC toy car to be controlled by the angle in which a hand was positioned.

My contributions:

Focused on all the programming of the used STM32F100 board, which use the Arm® Cortex®-M3 core. Created code for determining the position of the user controller (shown [here](https://github.com/fernandoaestrella/Motion-Controlled-RC-Car/blob/master/Motion%20Controlled%20RC%20Car/Programa/main.c)) through which a user could turn the sensor (an ADXL335 accelerometer) in any of 4 different directions (forward, backwards, left and right) and the car would move in any of the resulting direction (it could move forward, backwards, forward and right, forward and left, back and right, back and left, turn the wheels right, or turn them left). Final report [here](https://github.com/fernandoaestrella/Motion-Controlled-RC-Car/blob/master/Motion%20Controlled%20RC%20Car/Reporte%20Final.pdf) (in Spanish).

<img src="images/accelerometer.png?raw=true"/>

---

### Games

---

[SlideIn](https://github.com/fernandoaestrella/SlideIn) (Spring of 2020)

Solo developed a game made in Unity in which the player summons units in a table top gameboard. The goal is to slide your units into the opponent's goal tile. You can also remove an opponent's unit by placing 3 of yours in front of it.

To play:

Go to [SlideIn.exe](https://github.com/fernandoaestrella/SlideIn/blob/master/SlideIn.exe), download and run it.

To see code:

Go to [Assets](https://github.com/fernandoaestrella/SlideIn/tree/master/Assets) and look at the C Sharp files.

<img src="images/slide-in-image.png?raw=true"/>

---
[Actually Exciting Pong](https://github.com/fernandoaestrella/Actually-Exciting-Pong) (Spring of 2019)

Solo developed a variation of Pong in [Processing](https://processing.org/) with the following features:
- Ability to shoot multiple shots
- Paddle freezes for some time when hitting the ball
- Paddle gets smaller after every hit
- Shot accelerates or slows ball depending on whether the ball was approaching or going away
- Score per time calculation
- Ball accelerates after hitting paddle
- Ball goes more red the faster it goes

<div align="center"> <img src="images/excitingpong.png?raw=true"/> </div>

---
