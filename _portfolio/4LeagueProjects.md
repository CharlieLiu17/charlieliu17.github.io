---
title: "League Of Legends Projects"
excerpt: "Check out what I do with my favorite hobby."
order: 4
header:
    teaser: ../images/league-thumbnail.jpg
sidebar:
    - title: "Role"
      text: "Software Engineer"
    - title: "Responsibilities"
      text: "Software Design, Software Development"
    - title: "Technologies"
      text: "PHP, WordPress, Python, REST APIs (Riot/YouTube)"
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
  .caption {
    margin: 10px auto;
    font-size: 0.75em;
    font-style: italic;
    text-align: center;
  }
</style>

## Purpose

I have a lot of passion for the game of League, so this page houses the League-related projects I've worked on.

## Freelance Development with Skill Capped (8/22 - Present)

Skill Capped is a very popular YouTube channel and website **(1.2 million+ total subscribers)** that provides high-level educational content for games like World of Warcraft, Valorant, and League of Legends. Their guides have personally helped with my own journey with League of Legends, so I was very excited for this opportunity.

Skill Capped reached out to me to help develop features for the launch of their new website. I created a **dynamic tierlist Wordpress plug-in**. 

<div class="flex">
  <iframe class="flex-item" width="560" height="315" src="https://www.youtube.com/embed/rw9ujr2470w?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div class="flex">
  <div class="caption flex"> The current WIP of the dynamic tier list. <br> Currently with WoW, to be expanded to League and Valorant.</div>
</div>

I'm continuing my work with Skill Capped, so I can produce more features for them and their subscribers and to stay close to the gaming space!

## ```championsearch.py```

Running ```championsearch.py``` allows you to input your champion, the enemy champion (usually your lane opponent), and the key ability of your champion and the enemy champion to compare. The output is both champion's ability cooldowns, as well as the cooldown difference between your key ability and the enemy's. An example is shown below: 

<div class="flex">
  <img class="flex-item" src="../../images/League/output.JPG" />
</div>

Additionally, the program will open up the op.gg champion page and a YouTube video. The video showcases a high-elo game where the champion you play wins against the enemy champion.

<div class="flex">
  <img class="flex-item" src="../../images/League/video_output.JPG?raw=true" />
  <img class="flex-item" src="../../images/League/opgg.JPG?raw=true" />
</div>

### When to use ```championsearch.py```

```championsearch.py``` is a great tool to use before you get into game. The text output allows you calibrate how long each ability's cooldown is for the enemy and gets you in the mindset of thinking of which key ability the enemy has you need to be wary of. As for the links, the op.gg page allows a player new to a champ quickly understand what abilities to max, items to build, etc. Yet the most important functionality may be the video. The video lets you quickly get into the specifics of a matchup, giving the player model gameplay and allowing them to emulate it.  
