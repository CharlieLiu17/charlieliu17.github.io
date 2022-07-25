---
title: "Deadliest Catch"
excerpt: "Tower defense game built in Android Studio for CS 2340."
header:
    image:  ../images/DeadliestCatch/deadliest-catch-thumbnail.png
    teaser: ../images/DeadliestCatch/deadliest-catch-teaser.png
sidebar:
    - title: "Role"
      text: "Lead Software Engineer"
    - title: "Responsibilities"
      text: "Game Development"
    - title: "Technologies"
      text: "Java, Android Studio"
    - title: <a href="https://github.com/CharlieLiu17/DeadliestCatch"> Github Repo </a>
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
  }
</style>

<div class="flex">
  <video class="flex-item" width="100%" height="auto" controls autoplay muted loop>
    <source src="../../videos/DeadliestCatchDemo.mp4" type="video/mp4">
  </video>
</div>

## Description
Deadliest Catch is a tower defense game built in CS 2340: Objects and Design by Charlie Liu, Amal Chaudry, Tina Nguyen, Swati Murugappan, and Morris Wan. Once a level is selected, the player can choose any unit (fisherman, spearman, or boatman) to place along the river side. These units have specialized effects, and the player must choose what combination of them most effectively stops the oncoming fish from reaching the end of the river!

## The How

Deadliest Catch was developed in 2-week milestones, akin to Agile Sprints. In this project, we had design meetings that let us implement software design patterns like singletons, as well as utilizing polymorphism and inheritance at a high-level. Additionally, we implemented our own game engine code by creating a robust frame system, allowing us to freely adjust the frames per second (FPS), to a maximum of 90 FPS. This gives the game a much smoother feel than games created by other teams. Additionally, while other teams used tiling systems to determine hitboxes and placement of units, Deadliest Catch has pixel precision for these systems. This gave amazing freedom to the player to strategically place their units and also get immediate feedback for combat.