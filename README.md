# Analog Recording and Introduction to MAX 8

At the end of the session, you will have created an audio recording, and done your first patch with MAX 8.

This repo (short for repository) contains the activities for this session. If materials are referred to here, download the respective repository as a zip file, unpack it if necessary and then use its contents while working on the tasks outlined here in this README file.

![Audacity with Learning Music](/media/2024-01-09_07-57-54.png)

## What will you do today?

- [ ] Install Audacity and MAX 8
- [ ] Record your first composition made with Learning Music by Ableton and record it with Audacity
- [ ] Do some basic editing of your recording and export the recorded file as .mp3.
- [ ] Create your first MAX patch (program) and make use of your audio recording.


### Installing Audacity and MAX 8

## macOS (Apple M1 or newer)

On an Apple computer you need to install a special audio plugin in addition to Audacity and MAX 8. Here are the instructions:

### Install BlackHole Plugin and Configuration

This plugin runs on Apple M1/M2 and is required if you want to make recordings of sound coming from “within” your computer (sound from a website) Go to [BlackHole](https://github.com/ExistentialAudio/BlackHole)

1. Download and install the BlueHole Application for 2ch
2. Follow the instructions in [Setup Multi-Output-Device](https://github.com/ExistentialAudio/BlackHole/wiki/Multi-Output-Device)


## Audacity (For Windows and macOS)

- Install and launch Audacity(https://www.audacityteam.org)
- **For macOS:** Select BlackHole 2ch in Audio Setup / Recording Device
- **For Windows:** Select Windows WASAPI in Audio Setup / Recording Device


## Install MAX 8

### School PC: 
1. Find MAX on the netsoft repository and install it (takes time, big application)
2. You are ready to go.

### BYOD: 
1. go to [cycling74](https://cycling74.com/downloads) and download MAX 8 for your operating system.
2. Then install MAX 8.
3. In order to use MAX beyond the 30 days trial version, you need to install a software keyfile on your computer. Ask the teacher for help set it up on your computer.


## Play some music and record it with Audacity
1. Find [Learningmusic by Ableton](https://learningmusic.ableton.com/index.html)
2. Get to know the the Music Device on the homepage and create some songs
3. Record your song with Audacity
4. Export the audio file as mp3


### Audacity settings for Windows 10, recording and sound editing

The video below demonstrates how to set up, record, and edit a sound recording. While the video shows an older version of the Audacity software on Windows, it still applies for macOS and newer Audacity versions, so have a look and follow the guide to record and polish your audio recording.

<iframe width="560" height="315" src="https://www.youtube.com/embed/knL6uKBGyIg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


#### Only for those that have a GitHub Pages site

The code snippet below adds an audio player that allows you to play the mp3 file "220516Rec1.mp3" that has been saved in the folder "assets" inside your repository to show on your website. The Name of the Audio file and the path to where it is saved in your repository may vary if you have a different setup.

``` language=html
<div>
  <audio controls>
    <source src="/assets/220516Rec1.mp3" type="audio/mpeg">
  </audio>
</div>
```


## Learn about MAX 8

Get started with MAX 8 - Get to know MAX 8 and create your first patch with MAX (programs are called patches), [here](https://youtu.be/XQIWh4AnluI) is a Youtube video that gives you a first introduction. You will learn to assemble a small two channel playlist and control it with buttons.![audioplayer](/media/221108_AudioPlayer_in_MAX.png)

If you want to learn more, have a look at this [video](https://youtu.be/-4nZ6wnVdY8) that also introduces you to MAX. Learn by patching and just recreate the patch introduced and then discover what happens when you remix the patch to tweak it doing other things.
