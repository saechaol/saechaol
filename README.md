# saechaol

I'm a graduating senior at Sacramento State, and will earn my B.S. in Computer Science with a certificate in Game Engineering in May 2021.

## Selected Projects

### [Capstone Project: TrafficSim](https://pastachefs.github.io/trafficsim/) **(To be completed: April 2021)**

<img alt="Screenshot of a car in-game" src="https://pastachefs.github.io/trafficsim/assets/img/about.png">

[TrafficSim](https://pastachefs.github.io/trafficsim/) is a virtual reality application built on Unreal 4.23 (C++) for the Oculus Rift, controlled using a Logitech steering wheel input, developed by myself and my team. It is designed as a product to enable researchers to observe and model driver behavior and interactions in a realistic setting. The application presents to the user several different prebuilt maps to choose from, and also includes a built-in map editor, both of which are intended to be used by our client, with little technical ability required to use the software. While similar driving simulation tools already exist, this VR application comes without the same cost overhead to our client as dedicated driving simulation hardware, as the costs incurred for this project would be the Oculus and VR ready computer.

When the player is seated into the game world, they are loaded into any of the pre-built or user made maps, and every action, reaction or input made is logged into an external spreadsheet for further statistical analysis. The player is able to drive around in the various conditions, time of day, and road hazards, as well as interact with and avoid neighboring NPC cars.

Planned feature roadmap includes:
* Adding more road types such as intersections and highway interchanges
* Adding stop signs, traffic lights, and construction/school zone signs
* Allowing the user to save their custom map
* Traffic density control, so the user/researcher can input a hard value (0 ... 1.0) for NPC generation
* NPC behavior control, so the user/researcher can specify NPC aggressiveness
* Dynamic and real time weather conditions, currently only fog density is implemented
* Programmable and timeable pedestrian behavior
* A scenario editor, so the user/researcher can load a specific combination of maps and map settings for more consistent observation environments.

I am also responsible for maintaining the project website.

### [Mobile Learning Application](https://github.com/saechaol/learning-app) **(Completed December 2020)**

#### The EC2 instance containing the .NET application providing the web service is currently suspended to reduce costs at my personal expense. In lieu of this, the following video demos some of the features described in this project [[demo link](https://youtu.be/YFPar6fbaAc)]

<img alt="Application home page screenshot showing Students, Courses, and Instructors category buttons" src="https://github.com/saechaol/learning-app/blob/main/image.png" width=35% height=35%>

A [learning application](https://github.com/saechaol/learning-app), built using Android Studio and Visual Studio which supports registration, communication, and task scheduling, that communicates directly with an AWS EC2 instance with a .NET application providing a REST API endpoint and an RDS backend layer. The application client itself is built using Java, and it connects to an RDS instance which stores user information, class schedules, and tasks.

There are several API controllers implemented in C++ in the .NET application that the client uses to fetch data relevent to each screen, as well as update user, subject, and task information to the database. Each POST method is protected using an implicit transactions to prevent mishandling of data should the service be interrupted mid-request. The webservice itself is load balanced using AWS's built in featureset for EC2 instances, and SSL certificate to serve the endpoint over HTTPS.

### [Postcards](https://github.com/saechaol/fullstack-vue-graphql-web-app) (To be completed: February 2021)
 
 <img alt="Figma prototype screenshot showing an example post with likes, title, and a description" src="https://github.com/saechaol/fullstack-vue-graphql-web-app/blob/master/readme_images/3.png">
 
I am currently working on building a responsive full-stack web application named [Postcards](https://github.com/saechaol/fullstack-vue-graphql-web-app) that supports secure user signup, login, authentication, photo posting, tagging, liking and commenting, using the Vue.js framework on the frontend and MongoDB Atlas on the backend. Data is fetched and mutated through GraphQL API endpoint that interfaces with the database. The project is prototyped on Figma and I am expecting to complete it by mid-February. 

### [Simple iOS Calculator](https://github.com/saechaol/ios-calculator) **(Completed October 2020)**

<img alt="Calculator screenshot" src="https://github.com/saechaol/ios-calculator/blob/main/Asset/Screenshot.png" width=35% height=35%>

[Simple iOS Calculator](https://github.com/saechaol/ios-calculator) is a small side-project to practice iOS development and Swift. It is a simple calculator app that supports basic arithmetic operations (addition, subtraction, multiplication, division, modulo), single-line history, deletion, and unit conversion between octal, decimal, binary, and hexadecimal formats. It also supports bitwise operations including AND, OR, XOR, and NOT.

## Ongoing Coursework

The following is/are a rolling/tentative list of other projects planned as per my coursework for the current semester:
* [An OpenGL application](https://github.com/saechaol/csc-155) to render a 3D scene which will incorporate shadow mapping, a skybox, normal mapping, tessellation shaders, geometry shaders for primitive modification, atmospheric fog and opacity, environment mapping, 3D textures/perlin noise generation, stereoscopy with distortion correction, fresnel reflection, light refraction, and ray tracing. The project will be hosted on the linked repository.

<!--
**saechaol/saechaol** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
