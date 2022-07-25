---
title: "WriteNoise - 2nd Place @ HackGT7"
excerpt: "Visualizing sound with applications in steganography and artistic musical representation."
header:
    image:  ./images/writenoise-hero.png
    teaser: ../images/writenoise-thumbnail.JPG
sidebar:
    - title: "Role"
      text: "Project Manager, Software Engineer"
    - title: "Responsibilities"
      text: "Idea Generation, Project Management"
    - title: "Technologies"
      text: "Python, SciPy, NumPy, MatPlotLib"
    - title: <a href="https://github.com/CharlieLiu17/WriteNoise"> Github Repo </a>
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

WriteNoise was a HackGT7 project made by Charlie Liu, Morris Wan, Ethan Chee, and Kurt Hu. It won **2nd Place Overall** in the hackathon, out of 2500+ participants.

<div class="flex">
  <video class="flex-item" width="100%" height="auto" controls loop>
    <source src="../../videos/WriteNoiseDemo.mp4" type="video/mp4">
  </video>
</div>

## What is WriteNoise?

WriteNoise is a sound to image converter. How can we convert a sound to an image? Well, we convert every bit of sound into the bits of an RGBA value. Each RGBA value then becomes a pixel in the final image.

## Why would you use WriteNoise?

WriteNoise has many applications. From steganography to artistic musical representation, it's truly versatile.

Since this is a lossless conversion of information, you can use the produced image as an encrypted message that has the additional benefit of an extra layer of protection as people wouldn't even realize it's a message. 

Additionally, the produced image can be used as a "QR code" for sound. Without an internet connection, a QR code is often only a text string. Our image could let sound be played without an internet connection.

Finally, the produced image can represent different types of sound. The laughter at a comedy show produces a drastically different image than the sound of Taylor Swift's  hit song, "22".

## Demo

https://writenoise.herokuapp.com/

Only takes .wav files.

## More information

More information can be found on [Devpost](https://devpost.com/software/write-noise)!
