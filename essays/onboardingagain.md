---
layout: essay
type: essay
title: "Baby Steps"
date: 2018-08-29
labels:
  - Engineering
  - TechFolios Designer
---
For my first actual experience with the TechFolios code, I was asked to make six basic improvements. These improvements and their solutions are listed here.

<h2>1. Change background color of Splash Page</h2>
For my first task, I had to change the background color of the Splash page, which is the default screen, to light grey. Becaue this was my first time poking around the code, I gained a little bit of insight as to how the code was organized into folders.

<img class="ui centered image" src="https://i.imgur.com/tNLUioe.png" />

After changing the code, which was a very simple add-in, I also learned that the HTML and CSS styling was smack dab in the middle of the code.

<img class="ui centered image" src="https://i.imgur.com/dORdH5p.png" />

As you can see here, the background color for the Splash page is indeed grey.
<h2>2. Add "last modified" timestamp to Splash page</h2>
The second improvement was adding a "last modified" timestamp row to the table on the Splash page. Due to the wording of the spec, I initially thought that I would need to create a way to update said row on the Splash page any time something on the Splash page was edited. While this way of thinking isn't necessarily wrong, it makes the solution to this problem many many times more complicated. Instead of going through individual methods and making sure to update the time any time one of them was used, I could instead update the row in the Splash page every time the table was re-rendered. This way, all I had to do was write the current time the instant the table was rendered, and I would effectively have a "Last modified" timestamp.

<img class="ui centered image" src="https://i.imgur.com/zdR0RVi.png" />

What I was originally trying to create would have taken many lines of code, and admittedly, I wasted an embarassing amount of time trying to make that work. One can only imagine how frustrated I was when I figured out that what I thought was a moderately difficult problem only took a few lines of code to solve.

<img class="ui centered image" src="https://i.imgur.com/VCSmHoT.png" />

The end result works perfectly.
<h2>3. Add menu item to Config menu.</h2>
After my perils solving the second issue, the third issue was certainly a sight for sore eyes. All I had to do was add an extra menu item to the Config menu. This option was to indicate the current time in a notification window.

<img class="ui centered image" src="https://i.imgur.com/tPLbMAF.png" />

All I had to do was find the options for the Config menu and add another option. After that, it was a simple solve using the same current time function from the previous task, with the added caveat of displaying it in a notification window.

<img class="ui centered image" src="https://i.imgur.com/YetNCDh.png" />

<h2>4. Add simple validation to Set GitHub Repo name</h2>
The fourth task was also a relatively simple task. There was already a validation system in place for the GitHub Repo name, so all I did was look at that information and add more to it in order to check for ".github.io" at the end of the string.

<img class="ui centered image" src="https://i.imgur.com/VHKOeCc.png" />

I wasn't 100% confident with regex, so I looked up the syntax in order to properly implement this solution.

<img class="ui centered image" src="https://i.imgur.com/od9ifTS.png" />

<h2>5. Allow four networks in the Simple Bio Editor</h2>
This task was probably the easiest out of all of them, minus the first task. 

<img class="ui centered image" src="https://i.imgur.com/01u31zQ.png" />

The Networks tab was already implemented with three networks, and so all I had to do was add an extra field for every piece of a network, and voila; now there are four networks.

<img class="ui centered image" src="https://i.imgur.com/Pry0YOE.png" />

After a little bit of testing to make sure all four networks properly, I moved on to the final task.
<h2>6. Perform simple validation on Project and Essay files.</h2>
Much like the second task, I unfortunately thought way too hard about this question, and when I finally created a working solution, it only took about four measly lines of code.

<img class="ui centered image" src="https://i.imgur.com/w4jNz3K.png" />

When I first started working on this question, anything I did to the function I was working with, saveFile, would break it, causing the editor to fail to even load anything. On top of that, I wasn't even sure at first whether saveFile was the correct place to be looking. But what was even worse was that no matter what I tried, I just couldn't seem to get the notification system working. After countless attempts, I resorted to looking at our group's Slack channel to see whether other people had had problems as well, and lo and behold, they had. 

<img class="ui centered image" src="https://i.imgur.com/E9oaU9B.png" />

I eventually went with a solution that my classmates had also implemented, which was using a module called node-notifier. This changes the message into a notification instead of a window, however, so this is something that I'd like to change in the future if possible. 