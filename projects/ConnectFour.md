---
layout: project
type: project
image: img/Connect Four.jpg
title: "Connect Four"
date: 2019-03-07
published: true
labels:
  - Java
  - Game
summary: "I made a Connect Four game with a computer player in my AP Computer Science class."
---

<div class="text-center p-4">
  <img width="200px" src="../img/Connect Four.jpg" >
</div>

The assignment was basically to recreate the game, played by two players that inputted the column they wanted to place their piece in. I also made a computer player for fun. It makes the "best move" at the current turn but doesn't account for multiple moves ahead (like in chess), and it can be predictable at times since I didn't make an RNG element for when there are multiple "best moves", but is still a decently strong opponent. Even without making my own computer player, I learned how to account for multiple possible future scenarios to make sure that my code doesn't break.
