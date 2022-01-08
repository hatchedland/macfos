---
layout: projects_layout
card_img: 'https://hackster.imgix.net/uploads/attachments/985495/uploads2ftmp2fb533d539-8f18-480d-8e4b-83afb97c04322fcapa_j1sJspuuR8.jpg?auto=compress%2Cformat&w=900&h=675&fit=min'
project_name: scoreboard
contributers: [ Abhishek, Rajan ]
date_started: 2021-10-12
---

# Scoreboard
![Creating an Electronic Scoreboard with Arduino](https://hackster.imgix.net/uploads/attachments/985495/uploads2ftmp2fb533d539-8f18-480d-8e4b-83afb97c04322fcapa_j1sJspuuR8.jpg?auto=compress%2Cformat&w=900&h=675&fit=min)
Many times we want to play something with friends and we need an electronic boards to count the points of each team or player. Based on this, we developed this project with [Arduino](https://www.utsource.net/itm/p/8647184.html).

The following project is to develop an electronic scoreboard with [Arduino](https://www.utsource.net/itm/p/8647184.html). Through this scoreboard, we will use two [buttons](https://www.utsource.net/itm/p/9221543.html) to adjust the score for each player or team.

Next, we will start the discussion and development of the project step by step.

## Story

Project Development

Initially, we present the electronic components used and the schematic assembly circuit of the project in Figure 1.

Through this circuit, we use two buttons to adjust the score on the electronic scoreboard.

The [button](https://www.utsource.net/itm/p/9221543.html) attached to digital pin 6 adjust player 1's points, while the button attached to digital pin 7 adjusts player 2's score.

Points will be sent by [Arduino Nano](https://www.utsource.net/itm/p/8647184.html) to the [TM1637 display module](http://www.utsource.net).

Next, we will start discussing the project programming code.

**The Logic Programming of the Electronic Scoreboard**

Following is the complete code for the development of the electronic scoreboard with Arduino. Soon after, we will present the step by step discussion of the project.



