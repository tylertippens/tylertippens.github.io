---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am a doctoral candidate and graduate research assistant in the School of Earth and Atmospheric Sciences at the Georgia Institute of Technology in Atlanta, GA.

I'm interested in utilizing the ever-increasing capability and accessibility of large-scale computing environments to enable new avenues of scientific inquiry. I have experience translating broad scientific goals concerning complex systems into quantitative, impactful questions which can be answered through a combination of computer modeling and data analysis. My expertise includes scientific software development, high performance computing, modeling and simulation, data analysis and visualization, and scientific communication.

My research focuses on the development of novel modeling techniques to enable imaging of moon-magnetosphere plasma interactions in the outer solar system using energetic neutral atoms. This work relies on the creation and application of performant, highly-parallelized simulation codes and on analysis and visualization of complex data products.

Over the course of a doctoral minor in scientific machine learning I've also had the privilege of working in two interdiscplinary teams on class projects utilizing ML. In collaboration with the Emory Neurology department, I was part of a group which assessed several supervised and unsupervised learning methods for categorizating the success of surgery on stroke patients using brain images. [Our final report can be found here.](https://codingsoo.github.io/CS-7461-Project/) The following semester, I helped write a project proposal on integrating a physics-informed loss function into the data-driven weather prediction model FourCastNet. [The proposal is available here (PDF).](files/CliML.pdf) These projects have fueled my interest in applying the expertise I've obtained doing space physics modeling, here on Earth.

Research Interests
======

Energetic Neutral Atom Imaging at Titan
------
Saturn's largest moon Titan is the only satellite in the solar system with a substantial atmosphere. I model the interaction between the moon's ionosphere and the planet's magnetosphere in order to learn about the character of this interaction and what it can tell us about the Titan itself.

I'm specifically interested in remotely sensing the moon-magnetosphere interaction using **energetic neutral atoms (ENAs)**. These are energetic ions from the plasma in Saturn's magnetosphere which pick up an electron from a particle in Titan's dense atmosphere, neutralizing them. They then fly off in straight lines, allowing them to be imaged in a manner roughly analagous to how a camera forms an image from light.

Extracting meaningful information from ENA images is difficult. I develop performant, highly-parallelized computer models that allow us to 1) study the global population of all ENAs that are produced at Titan, and 2) generate *synthetic ENA images* in a manner that mimics a real detector. In my [papers](publications) I've described how we use the global ENA model to describe how Saturn's every-changing magnetic field affects how ENAs are produced at Titan; and how we use synthetic ENA images produced by a second model to explore how the physics of the moon's plasma interaction are embedded in our observations of ENAs, such as in the images which have been taken by the Cassini spacecraft.
