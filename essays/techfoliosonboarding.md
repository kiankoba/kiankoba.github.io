---
layout: essay
type: essay
title: "TechFolios Designer: A New Chapter"
date: 2018-08-26
labels:
  - Engineering
  - Techfolios
---
As an IT student (and a senior at that) myself, creating a professional portfolio was always something that was on my list of things to do. Unfortunately, how to make a professional portfolio isn't something that's teaught in class, so I was at a bit of a loss in terms of how to start and what to do. Luckily for me, I was tasked with using <a href="https://github.com/techfolios/template">TechFolios</a>, a sort of template created by my ICS 314 professor, last year. The setup wasn't the most intuitive process, however, as it involved forking the aforementioned repo, and subsequemtly modifying and creating the JSON, md, and other files on my own. For someone with a lot of experience with computers, this process may only be mildly annoying, but for someone with little to no experience, setting up a portfolio may very well prove to be impossible.

In order to solve this conundrum, our professor developed an application called <a href="https://github.com/techfolios/techfoliodesigner">TechFolios Designer</a>, which is a simple GUI designed to make the setup and maintenance of a portfolio less painful. You can see an example image of me using this very UI here:

<p><img class="ui medium centered image" src="https://i.imgur.com/vBKCBwB.png" /></p>

This is the very program that I will in fact be helping to develop this coming semester. As a firsthand user of TechFolios and of the Designer application itself, I hope that I can bring a different perspective to the design team. Some of the problems that are already remedied with this application include editing of the bio.json file and creation and editing of the .md files used to represent essays and projects. As someone who had never even used such files before taking ICS 314, it was a bit of a journey learning how to properly format and use these files. One mistake and the project or essay in question would  never even appear, making it hard to diagnose errors in formatting, and editing the bio.json file would give unexpected results. With this application, however, there are simply GUIs that can be used in order to edit these files without hassle. In fact, I am using this very GUI to write this essay at this very moment!

The application is far from perfect, however. One thing that I did not like off the bat was the installer. Normally, one expects some sort of dialog asking for a directory to install the apllication, and in some cases, a list of options to choose from in regards to the installation, such as whether or not to create a desktop shortcut or start menu folder (on Windows). The current installer, however, has none of this, and simply goes straight to installing once you open it. In order to find out where the files were installed, I had to find the running process in the Task Manager and ask it to "Open file location" in order to find the directory it was running from. 

Another thing that would be nice to have would be some kind of file uploader. You may have noticed that I used an image in this essay, and normally one would expect this image to be uploaded or hosted together in the same place as all the other files, such as the very .md file which is used for this essay. I found it easier, however, to hose the image elsewhere, so I think it would be nice to have an easier way for users to upload files natively. 

Overall, I am very excited to be working on something that will hopefully help many other students who come after me. As a user myself, I hope to contribute change that will make a difference and improve the experience of many people to come.