# Hygge

original repo: https://github.com/kychris/ProjectHygge

## Inspiration
When physical space is constructed, architects, engineers, and interior designers use extensive knowledge of how humans interact with structures to create the best space for the needs of the people that will use it.

But we're here this weekend with hundreds of virtual builders, who are creating spaces without the confines of materials, cost, and physics!

How can we help the builders of virtual spaces create environments that provide the best experience for their users?

Hygge does that through the universal language of data.

## What it does
Let's say Gold’s Gym wants to create an interactive VR space to host workout classes. They want to provide two classes, Zumba and Yoga. For their yoga class, they want users to feel calm and focused. For their Zumba class, they want users to feel energized and happy. This is where Project Hygge makes the difference! By utilizing our tool, Gold’s Gym can create multiple versions of spaces embedded with different design elements (e.g. color of lights, room size, furniture choices) and track the emotions of users. Then, they can synthesize this data to create the best space(s) to enhance their user's experience. 

Project Hygge seeks to optimize the spatial design in the VR and AR industry by providing an engaging data-driven research tool with EEG. The testers can see their visualized EEG data, where three bouncing balls reflect users' focus, relaxation, and stress levels, respectively. UX researchers can use this data to inform how they build and design their virtual space.

VR can be a very overwhelming and highly emotional experience - it is imperative that creators consider how their users will feel in these spaces. Hygge gives them the tools to make more informed design decisions.

## How we built it
We mainly used Unity and Emotiv for the project. In Unity, we built a meeting room for testers to experience and a panel for researchers to change material, lighting, scale, etc with XRI, C#, and Universal render pipeline. Also, we built a bridge between Emotiv and Unity so the responsive mood ball UI can get the data from brainwaves.

## Challenges we ran into
We have met three major challenges along. First, we discussed a lot about the storytelling of our ideation since we hope this tool could be implemented in all VR spatial experiences. We figured the best approach is to create a use case - find the best virtual meeting room based on the attendees' preference. Second, we strengthened the weak Bluetooth signal and stabilized the brainwave sensor by dropping salty water and moving to other spaces. Lastly, integrating the Emotiv platform, Oculus Integration Package, and the packages needed for all of us to test on our devices involved a lot of "gluing", so we used the XR toolkits instead to simplify development. 

## Accomplishments that we're proud of
We collaborated on ideas and refined this one to something that we all believe is important, and **helps to advance XR.**

It works! We've got data from the EEG in usable and in Unity!

## What we learned
Two of the members of this team had less than 1 week of VR/Unity experience, so a lot was learned! For some of us, it was our first time working on a collaborative Unity project. 

Most of the team had never worked with EEG before, so it was interesting to see what types of information could be found, how the data was structured, and how it could be ported into Unity so that your brain could be used to literally change your environment 🤯

We also learned a lot about best design practices in our research. As people who are empowered by creating virtual spaces, we all care deeply about making sure VR is an inclusive tool that considers the psychological impact that space may have. We researched colors, textures, lighting, and proportions that make people feel comfortable.

## What's next for Hygge
We want VR creators to be able to make informed design choices and create spaces where users have the intended emotional responses.

As more spaces are tested, and more emotional responses are collected, a dataset will be created. That dataset can be used in machine learning models. Those ML models can be used to help gain a broader understanding of how people react to changes in virtual environments, and could even be used to create virtual spaces that adapt to a users emotions. 
