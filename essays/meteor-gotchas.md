---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---


As is probably the case with anyone learning a new concept, I made many mistakes in my journey to learning how to use meteor. Slow build times, incorrect usage of commands, and crashing code are just some examples of the things that went wrong when I started using meteor. 

The very first problem that I ran into when using meteor was installing it. I downloaded the .exe file and ran it, and it was supposedly finished. When I actually tried to use it, however, I had to run updates on meteor itself and for something called npm. Now usually there's a sort of "loading icon" that switches between the | / - \ | characters to indicate that the application hasn't crashed, but the characters had stopped changing multiple times when I tried to install the updates. Thinking that the program had crashed, I restarted and tried to update again, even going so far as to restart my machine and even looking for solutions online. However, I didn't find any solutions, so I instead tried just leaving the program alone for a considerable amount of time while doing something else, and, to my surprise, the update eventually went through. It turns out I was just thinking too hard about something that didn't even need fixing. 

<img class = "ui fluid image" src = "https://i.imgur.com/2K0FmEV.png">

Another mistake that I've made was forgetting import statements, and, more recently, not renaming a template correctly. In a recent school project I'm working on called digits, there is a template file that I modify to fit my own code. After refactoring what I thought was all of the references to the old code, I attempted running my program, and ran into a strange error where I thought that my CSS style was being overrun by the default CSS. I couldn't figure out whether I had missed an import (spoiler: I hadn't), or whether my variables were named correctly, or whether I had somehow missed a step or had written some code incorrectly. I even went so far as to make a new branch in an attempt to fix the problem, but to my frustration, I ran into the same exact bug again. I ended up having to ask my professor for help, and, to my embarassment, all I had done was forget to rename a template. An error had even appeared in the console for my project, but I hadn't even tried looking at the console, so I had no idea an error had even occurred. 

<img class = "ui fluid image" src = "https://files.slack.com/files-tmb/T624151AA-F7KTW1G5S-6604bef9a5/home-page-screen_1024.png">
<div class = "ui pointing label">My error.</div>

I'd love to blame my problems on meteor being a janky, hard-to-use application, but there's no denying that I was careless and that my incompetence led to failure. Fortunately for me, however, as I continue to work on more projects and become more familiar with meteor, I feel that I will be able to learn and grow into an even better software developer.
