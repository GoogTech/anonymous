---
title: 'saycheese : grab target''s webcam shots by link'
date: 2020-06-10 15:09:22
tags: [Exploit Android,Hacking Tool]
---


# `README.md`

# SayCheese v1.2
## Author: https://github.com/thelinuxchoice/saycheese
## Twitter: https://twitter.com/linux_choice

Take webcam shots from target just sending a malicious link

![sch](https://user-images.githubusercontent.com/34893261/81830116-10add880-9512-11ea-946e-3643db8c1bba.png)

# How it works?
<p>The tool generates a malicious HTTPS page using Ngrok Port Forwarding method, and a javascript code to perform cam requests using MediaDevices.getUserMedia. </p>

<p>The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types. </p>

[See more about MediaDEvices.getUserMedia() here](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)
<p> To convince the target to grant permissions to access the cam, the page uses as default template page a javascript code made by https://github.com/wybiral that turns the favicon into a cam stream.</p>

## Legal disclaimer:

Usage of SayCheese for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 
## Installing (Tested on Kali Linux 2020.1):

```
git clone https://github.com/thelinuxchoice/saycheese
cd saycheese
bash saycheese.sh
```
### Donate!
Pay me a coffee:
### Paypal:
https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CLKRT5QXXFJY4&source=url


# `Repo`
> *github repo : https://github.com/thelinuxchoice/saycheese*


# `Teching Video`
> *how to use it : https://youtu.be/_VhDxHkGCjs*


# `Frequent Issues`
> *can't get or only get blank picture : https://github.com/thelinuxchoice/saycheese/issues/34*