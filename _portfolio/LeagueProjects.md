---
title: "League Of Legends Projects"
excerpt: "Check out what I do with my favorite hobby."
header:
    teaser: ../images/league-thumbnail.png
sidebar:
    - title: "Role"
      text: "Software Engineer"
    - title: "Responsibilities"
      text: "Software Design, Software Development"
    - title: "Technologies"
      text: "Python, REST APIs (Riot/YouTube)"
    - title: <a href="https://github.com/CharlieLiu17/league-projects"> Github Repo </a>
---
<style>
  .flex {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    gap: 1em;
    flex-wrap: wrap;
  }
  .flex-item {
    border-radius: 10px;
  }
</style>

## Purpose

I have a lot of passion for the game of League, so this page houses the League projects I have worked on, currently working on, and future projects I will work on.

## ```championsearch.py```

Running ```championsearch.py``` allows you to input your champion, the enemy champion (usually your lane opponent), and the key ability of your champion and the enemy champion to compare. The output is both champion's ability cooldowns, as well as the cooldown difference between your key ability and the enemy's. An example is shown below: 

<div class="flex">
  <img src="../../images/League/output.JPG" />
</div>

Additionally, the program will open up the op.gg champion page and a YouTube video. The video showcases a high-elo game where the champion you play wins against the enemy champion.

<div class="flex">
  <img src="../../images/League/video_output.JPG?raw=true" />
</div>

<div class="flex">
  <img src="../../images/League/opgg.JPG?raw=true" />
</div>

### When to use ```championsearch.py```

```championsearch.py``` is a great tool to use before you get into game. The text output allows you calibrate how long each ability's cooldown is for the enemy and gets you in the mindset of thinking of which key ability the enemy has you need to be wary of. As for the links, the op.gg page allows a player new to a champ quickly understand what abilities to max, items to build, etc. Yet the most important functionality may be the video. The video lets you quickly get into the specifics of a matchup, giving the player model gameplay and allowing them to emulate it.  
