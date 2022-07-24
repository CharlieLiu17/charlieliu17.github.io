---
title: "Deadliest Catch"
excerpt: "Automatic athlete analysis for any sport - figure skating, basketball and more!"
header:
    image:  ./images/techniq-teaser.png
    teaser: ../images/techniq-bigger-thumbnail.png
sidebar:
    - title: "Role"
      text: "Founder, Lead Software Engineer"
    - title: "Responsibilities"
      text: "Idea Generation, Project Management, Fullstack Development"
    - title: "Technologies"
      text: "Python, OpenCV, GoogleMediaPipe, React [in development]"
    - title: <a href="https://github.com/CharlieLiu17/Techniq"> Github Repo </a>
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

Techniq is an automatic athlete analysis app that can be used for virtually every physical sport. Techniq takes professional footage the user inputs (i.e. Steph Curry shooting a basketball) and also takes the user's own footage (i.e. themself shooting the basketball). Techniq can sync the two footages down to the frame and will then give you frame by frame comparison of the user's form against the professional. Techniq will give differences in form in degrees for all parts of the body.

## Examples

Below you can find 2 video clips: One of me shooting the basketball, and one of Steph Curry shooting the basketball.

<div class="flex">
  <video class="flex-item" width="auto" height="400" controls autoplay muted loop>
    <source src="https://user-images.githubusercontent.com/50965230/177166271-6b589611-bdd9-41f7-a88c-261ab094071c.mp4" type="video/mp4">
  </video>
  <video class="flex-item" width="auto" height="400" controls autoplay muted loop>
    <source src="https://user-images.githubusercontent.com/50965230/177166466-c55cc1dd-3aa2-4dea-bbae-6f7618bdd61e.mp4" type="video/mp4">
  </video>
</div>
<div class="caption">As evident by leaving the two videos playing, these video clips are not synchronized.</div>


Running the program on these two inputs, the result generated is a series of side-by-side frames: 


<div class="flex">
  <video class="flex-item" width="100%" height="auto" controls autoplay muted loop>
    <source src="https://user-images.githubusercontent.com/50965230/177167812-9726e84a-3cda-4e6a-b74d-05a9f2544cc1.mp4" type="video/mp4">
  </video>
</div>
<div class="caption">We rise at the same time and shoot at the same time. Differences in form now can be much more easily discerned.</div>

Another example with the figure skating jump, the **axel**.
Here are the initial clips:

<div class="flex">
  <video class="flex-item" width="100%" height="auto" controls autoplay muted loop>
    <source src="https://user-images.githubusercontent.com/50965230/180627533-3702b083-f3a9-4df0-a0f0-0421e58e5d87.mp4" type="video/mp4">
  </video>
  <video class="flex-item" width="100%" height="auto" controls autoplay muted loop>
    <source src="https://user-images.githubusercontent.com/50965230/180627534-76347d69-1213-4f08-b7e8-d74ed2c65a32.mp4" type="video/mp4">
  </video>
</div>

And here is the output:

<div class="flex">
  <video class="flex-item" width="100%" height="auto" controls autoplay muted loop>
    <source src="https://user-images.githubusercontent.com/50965230/177243187-7b14fb76-bcaa-4736-a4ec-3dd9cab62f23.mp4" type="video/mp4">
  </video>
</div>
<div class="caption">I (on left) am doing a double axel while Yuzuru Hanyu (on right, 2-time gold Olympic medalist) is doing a triple axel, which is one more rotation.  </div>

Notice even with significantly different camera angles, Techniq can still correctly synchronize.

## Who is this for?

Techniq should be used by athletes and coaches alike for form training.

Athletes are never always under the watchful eye of a coach. And while this app obviously can't completely replicate a coach, it can be a pivotal tool that speedens the learning feedback loop for the athlete.

Coaches can also greatly benefit from this. An athlete and a coach have limited time together, and that time is wasted if the two of them stand around for the coach to manually sync the videos. Additionally, the app may even spot faults in form that even the coach could not detect in real-time.

## Why did we make Techniq?

 Techniq was a product of a HackGT8, by Team STAC. STAC was composed of Charlie Liu, Amal Chaudry, Tina Nguyen, and Sheza Chaudhry. I came up with the idea, as I was an elite figure skater in high school and had experience using Google MediaPipe and OpenCV. I had a personal need for the app, and even after HackGT8, have continued to work on it. I'm currently actively building out the app, hoping to bring it to mobile in the near future.
