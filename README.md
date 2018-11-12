# Recording Setup

## Objective

This document outlines the steps and resources you can use to record talks using the Dev Edmonton Society recording gear. Talks recorded with this setup are suitable for upload to a video archive like YouTube, or can be live streamed where bandwidth and connection allows.

## Pre-requisites

### Hardware

#### [Epihan AV.io HD video grabber](https://www.epiphan.com/products/avio-hd/)

My favourite piece of kit in our little setup, this captures virtually any HDMI video and outputs over USB as a generic webcam video source in 1080p at 60 frames per second. There are no drivers needed on Windows, Mac, or Linux and it delivers a continuous video stream even when HDMI is connected and disconnected multiple times over the course of a night.

I have had issues with it outputting odd video sizes when outputting from presenters laptops, so I recommend downloading [the configuration tool from the resources on their website](https://www.epiphan.com/products/avio-hd/resources/). You can use this to check out native resolution coming into and out of the AV.io which can be useful if you have any issues with OBS (more on that later.)

#### USB Audio Capture

We’ve got a simple USB audio capture box which takes two XLR inputs (the large microphone connections) and exposes them as a USB audio source. No drivers are required and it just appears as another microphone in your audio settings.

#### [Saramonic Wireless Lavalier Microphone System](https://www.amazon.ca/gp/product/B01IMJDW9Q/ref=oh_aui_search_detailpage?ie=UTF8&psc=1)

This wireless microphone comes in a paired transmitter / receiver. They each take 2 AA batteries, so please make sure you check battery levels and replace them before each recording.

#### [Logitech BRIO](https://www.logitech.com/en-ca/product/brio)

We’ve recently upgraded our webcam to a new 4K HDR model. Given we’re often recording speakers in poor lighting conditions, the extra pixels and adjustable HDR has greatly improved the quality of the speaker videa. You’ll want to make sure that you also [download the camera settings software](https://support.logitech.com/en_ca/product/brio/downloads) to configure the camera as you can use it to zoom in and follow the speaker as they talk.

#### USB Hub

With all the accesories, you'll want a USB hub to connect it together. I usually plug the HD video grabber directly into my laptop, then run everything else through the hub.

#### HDMI Splitter

We use an HDMI splitter so that we can have two copies of the presenters laptop video. One goes up to the projector, and the second runs into the recording laptop.

#### HDMI Cables

You'll need an HDMI cable from the presenter to the splitter, then again from the recording laptop to the 

#### Projector

## Software

#### Open Broadcast Studio (OBS)

* [YouTube recommended recording settings](https://support.google.com/youtube/answer/1722171?hl=en-GB)
* [OBS Screencasting settings](https://www.mistergoodcat.com/post/screencasts-with-open-broadcaster-software)
* [Removing background noise in OBS](https://medium.com/@Wootpeanuts/removing-background-noise-with-obs-studio-17214d967fe0)
* [OBS YouTube settings](https://obsproject.com/forum/threads/your-videos-will-process-faster-if-you-encode-into-a-streamable-file-format.70734/#post-302313)
* Use MOV on Apple if you want the option to edit in iMovie, don't use MP4
* Downsample audio to mono in input source advanced settings, and in audio settings
* Monitor and output if you want to listen to the recording with headphones
* Check speaker desktop resoultion from AV.io using config and set OBS to same (probably not a preset)

#### AV.io Configuration Tool
#### Logitech Brio Configuration Tool
#### Sound Recorded / Quicktime

## Before The Day Of The Recording

Verifying and testing as much in advance of the recording will give you peace of mind and confidence that everything will go smoothly when it comes time to record the actual event. Remember that you'll often have a large crowd gathered, who aren't  interested in any A/V or technical issues, so troubleshooting while the audience waits is never a good idea. With that said, let's do our best to get you setup in advance!

### Decisions, Decisions

Before you start setting anything up, make sure you know what you're going to be doing!

#### Livestreaming vs Recording

The first thing you need to decide is whether you're going to live stream or just record your talks. There are pros and cons to each option, and what you decide to do will impact the setup you configure later.

Many people assume they'll want to livestream. It's fun to share what you're doing with the Internet and can be a great way to get community involved that can't attend in person, however you should be aware that without a stable **upstream** connection your viewers won't be able to see what you're doing or participate. YouTube recommends that you have a connection able to hold a stable 2.5 MB/s upstream with <30ms ping, however a connection of at least 5 MB/s and <10ms ping is ideal. It should also be stable enough that it won't drop out due to interference or other traffic on the network. Make sure to test connection well and let others know you'll be broadcasting!

You should also consider the streaming service you're going to use. Dev Edmonton has a YouTube channel that all members are welcome to use. As it's got more than 100 subscribers you can access features like live chat, however you're also welcome to use our hardward with your own channel if you prefer. There are also other great services like Twitch or Facebook Live you should consider. They all work with OBS, so this decision mostly comes down to the streaming features and audience you're trying to reach.

Finally, when livestreaming you need to decide how involved the audience can be in your broadcasts. Are presenters going to take questions from the livestream chat? Which questions and how do they get their turn in line to ask? Is there a moderator that passes questions on to the presenter? If so, who does this? Will the audience attending the event in person be made aware of the livestream chat? Again, the answers to these questions depend on your audience and goals, but you should consider them in advance.

Given the added complexity of livestreaming, many organizers choose to simply record their talks and post them online at a later time when they know that internet is reliable and fast. This is a good starting point if you're just getting started or using an unknown or unliable internet connection during the presentation.

A third option is to both stream and record talks. OBS is able to do this out of the box, though it can put an extra demand on your recording gear if you're streaming and recording at two different qualities. By doing so you can gain the interactivity of a livestream along with the fidelity and reliability of a recording. As always, whatever you decide, make sure to test it in advance!

#### Online vs Offline Editing

The other big choice you'll need to make is about online or offline editing of your recordings.

With online editing, you mix all audio and graphics in real-time during the recording of the presentation, and are left with a recording that's ready for sharing as soon as the event is over. This is great because it reduces the efforts and time needed to get talks and vidoes up after an event, but also makes the actual recording a little more stressful as you're trying to juggle extra scenes and sources you might not otherwise have to work with during the recording.

Offline editing is the other way to go. In this setup you simple record the speaker and their desktop at the event, then use a program like iMovie to add titles and credits afterwards. This eases some of the pressure at the time of recording, which is great especially when you're starting out, but it adds extra time after the event editing the vidoes. You also have to take special care to make sure you record in a format that your editor can work with (MOV if you're using iMovie.)

This guide will walk you through setting up scenes that can work for both offline and online editing, but you should decide before the event which you'll use and want to make sure you've got the appropriate scenes prepared in advance and are confident you can work with a recording in your chosen editor.

### Equipment Checklist

* [ ] AV.io video grabber
* [ ] USB audio capture
* [ ] Wireless lavalier microphone
* [ ] transmitter
* [ ] receiver
* [ ] Logitech BRIO Webcam
* [ ] HDMI cables x 2
* [ ] Fresh AA batteries x 4

### Pre-Recording Checklist

* [ ] Remind speaker to repeat questions
* [ ] Line up speaker and zoom with camera
* [ ] Do a test recording with audio and verify speaker title, each scene, and sponsors thank-you
* [ ] Check each input video AND audio source to make sure they're outputing and being recorded
* [ ] Check free space on the recording computer
* [ ] If streaming, verify that 

## Troubleshooting

### Presenter desktop video looks "chunky" and scaled

Use the AV.io tool to check the native resolution coming over HDMI from the presenter, then open the presenters desktop video source in OBS and set the resolution and refresh rate to match. Note, that you might need to move the desktop around in the scene if the resolution has changed.

### No audio in recordings or flame chart

This can happen for a few reasons. Start with the basics.

1. Open your systems sound settings and verify that your getting sound from the speakers microphone.
2. Check that the speakers microphone is on, has full battery power, and is not muted.
3. Restart OBS (changing some settings can sometimes require a restart)

If the audios still not back, then open *"Settings"* and check:

4. From the *"Output"* pane on the left select the *"Recording"* tab and then ensure that *"Audio Track"* has a checkbox beside *"1"*, like this:

[ AUDIO TRACK SCREENSHOT ]

5. Carry on to the *"Audio"* pane on the left and make sure that extra devices like *"Desktop Audio Device"* and *"Mix/Auxillary Device"* are disabled.

6. Confirm that the audio source is added to the scene you're on.
7. Open the audio source's properties (right-click, double-click or hit the gear icon) and try changing the audio device and hit OK, then change it back to what it's supposed to be on.
8. From the menu select *"Edit"* > *"Advanced Audio Properties"* and check which audio tracks the audio source will output too. Make sure track *"1"* has a checkbox as this is the track we're using in the recording. Also, confirm that *"Audio Monitoring"* is not set to *"Monitor Only (mute ouput)"* as that will mute the output in the recording. Finally, confirm that *"Downmix to Mono"* is checked as that's usually what you want for our speakers.

Confirm all of these settings, then if things still aren't working restart OBS one last time. If you're still having trouble then consider rebooting the system or trying another machine for recording. After the event, please consider posting an issue on this repo and reaching out to us on our Slack to figure out what was going wrong.
