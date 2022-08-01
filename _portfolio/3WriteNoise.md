---
title: "WriteNoise - 2nd Place @ HackGT7"
excerpt: "Visualizing sound with applications in steganography and artistic musical representation."
order: 3
header:
    image:  ./images/writenoise-hero.png
    teaser: ../images/writenoise-thumbnail.JPG
sidebar:
    - title: "Start/End"
      text: "Oct 2020"
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

WriteNoise is a sound to image converter with lossless conversion, allowing for encoded messages (steganography) and artistic musical representation.

It won **2nd Place Overall** in the hackathon, out of 2500+ participants.

<div class="flex">
  <video class="flex-item" width="100%" height="auto" controls loop>
    <source src="../../videos/WriteNoiseDemo.mp4" type="video/mp4">
  </video>
</div>

## How does WriteNoise work? 

It converts every byte of sound into the bytes of an RGBA value. Each RGBA value then becomes a pixel in the final image.

## Why would you use WriteNoise?

WriteNoise has many applications. From steganography to artistic musical representation, it's truly versatile.

Since this is a lossless conversion of information, you can use the produced image as an encrypted message that has the additional benefit of an extra layer of protection as people wouldn't even realize it's a message. 

Additionally, the produced image can be used as a "QR code" for sound. Without an internet connection, a QR code is often only a text string. Our image could let sound be played without an internet connection.

Finally, the produced image can represent different types of sound. The laughter at a comedy show produces a drastically different image than the sound of Taylor Swift's  hit song, "22".

## My Role

Over the course of 36 hours, I accomplished:
- Generating our idea
- Communicating effectively with HackGT judges
- Distributing work to 4 teammates
- Coding artistic features 

## Demo

https://writenoise.herokuapp.com/

Only takes .wav files.

## More information

More information can be found on [Devpost](https://devpost.com/software/write-noise)!

## Credits

WriteNoise was a HackGT7 project made by Charlie Liu, Morris Wan, Ethan Chee, and Kurt Hu.
