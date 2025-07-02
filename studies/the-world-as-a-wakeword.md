---
title: The World as a Wakeword
type: ""
date: 2025-07-02
display_date: "2022"
parent: "[[studies/always-learning|Always Learning]]"
tags:
  - writing
aliases: 
credit: 
format:
---

## Context

> I was invited to write a short chapter for the [edited exhibition catalog](https://art-museum.uq.edu.au/cimo), *Conflict in My Outlook*, for the two-part exhibition series _We Met Online_ (2020–2022, online) and _Don’t Be Evil_ (2021–2022). My installation [[studies/always-learning|Always Learning]], which was shown in _Don't Be Evil_, focused my attention on the existence and function of the 'wakeword'. The wakeword was an historically specific invention designed to produce consent but it was always flawed, always *not enough*, and destined to give way to a regime of total listening. 
> 
> I touch on this again in my notes on Prompting. Also, my lecture and then performance in [[studies/always-learning|Always Learning]] explored the limits of the wakeword through listening back to its captures and then group chanting of Siri, Alexa, and Google, to hold open the portal between the space of the installation and the space of the datacentre.

## Always Learning, the World as a Wakeword

The smart speaker is _always listening_. How could it hear the wake word otherwise?

For these devices, the wake word (for example, ‘Alexa,’ ‘Siri,’ or ‘Google’) is our assurance of consent, a literal code word that communicates a willingness to be listened to. But let’s consider some pseudocode of what happens:

```
listen(data):  
  if data.is(wakeword):  
    listenMore(moreData).until(listenMoreDuration)
```

Nevertheless, this is just a partial listening: we are placated by the knowledge that only the device that is listening and “no audio is sent to the cloud.”[^1] The Cloud is where the dark and mysterious shit happens so you’ve got to use the wake word to show that you’re ready to expose yourself in that way, aurally. The policeman in Louis Althusser’s notable example of interpellation says, “Hey, you there!” and when you turn to acknowledge that you have been recognized and addressed, you become a subject of the law.[^2] But this relationship is inverted when you share the stage with a smart speaker. This time it is you who speaks. When you say, ‘Hey, Google!’ however, it remains _you_ who is recognised and interpellated; you become a subject of Big Data.

We often can’t witness how we are recognised. We don’t have the opportunity to consent, or what we consent to at one moment is cynically taken as consent in an entirely different one. Or our consent is compelled by dependency and its boundaries are pushed, bit by bit. One of my early brushes with algorithmic power is interesting precisely because _I may otherwise never have known_ about this brush with power. In 2007, I began a Sisyphean performance of uploading every possible monochrome video to YouTube. A thousand days later, I received an automated copyright infringement notice, the first of many. An computational cop named ‘Content ID’ was doing a sweep of the Cloud and my early RGB videos were getting caught up as false positives, algorithmically accused of infringing on intellectual property, a patently absurd allegation for a video comprised of one single colour! It took me by surprise because while those videos had just been sitting idle, taking up disk space, a new form of automated surveillance had been developed and deployed without any fanfare. Other users had similar (non)experiences with their YouTube videos being repurposed as training data for machine listening applications (for example, AudioSet). This is an advantage of being a data aggregator: platforms can wait for the right moment to harvest data, and they can then harvest it again and again.

On the one hand, all of the accumulated data - gathered over decades now and concentrated in data centers - is a source of potential value for the corporations that manage them. Since it is impossible for the corporations to extract this value without automating the process - Google is certainly not going to hire people to tag, caption, and summarise billions of videos - they will instead develop machine learning models to sit at the heart of automated systems. On the other hand, these models can’t be built in the first place without collections of data. This is why machine learning breakthroughs in the 2010s had more to do with corporations’ monopolistic control of computing resources and data systems than with algorithmic innovation.[^3] Algorithms might have to wait decades for data abundance and a hospitable socio-political environment before actualising their potential.

In other words, data begets more data. Let me give a specific example. In 2007, Google launched a telephone number (800-GOOG-411) to provide a voice recognition service for people to look up phone numbers in North America. The acoustic model of GOOG-411 was combined with a language model from Google’s extensive web query data to develop Voice Search applications for mobile phones and desktop, which became yet another ‘ongoing flow of real usage data… supplying a steady flow of data for training systems.’[^4] By 2009, Google was able to start using its automatic speech recognition (ASR) models to systematically caption YouTube videos, extracting text from speech in the audio track. Not long after the first billion videos had been captioned, researchers in France created a new dataset called HowTo100M by using these captions to automatically split YouTube videos into short clips of humans narrating and performing visual tasks. This story doesn’t end, it iterates. HowTo100M will be used to train new models to further classify video and sound, shaping the steady supply of data streaming from ubiquitous sensors.

The AudioSet Ontology, developed by Google’s Sound Understanding team, is a hierarchical taxonomy of 635 kinds of sounds, from human sounds to animal sounds to environmental and man-made sounds. Its purpose is to help standardise and facilitate audio dataset development, giving anticipatory shape to all kinds of sonic data. AudioSet events, such as _dog barking_ and _glass breaking_, are already in use in Google home devices, and many listening devices industry-wide. Their deployment revises the pseudocode:

```
interestingEvents = [glassBreaking, kidsXBox, dogBarking, footsteps, microwave ...]  
  
listen(data):  
    if data.in(interestingEvents):  
       listenMore(moreData).until(listenMoreDuration)
```

There are more than 20 internet-connected devices in the average Australian home, many of which contain microphones. Increasingly, they treat the sound of the world itself as a wake word. Our consent will be assumed, anticipated, deferred, or delegated, and ultimately irrelevant, because when data begets more data there is no _safeword_.

---

[^1]: “Alexa Privacy and Data Handling Overview” (Amazon, Inc., July 2018).

[^2]: Louis Althusser, “Ideology and Ideological State Apparatuses (Notes towards an Investigation),” in _Lenin and philosophy, and other essays_ (London: New Left Books, 1971), 127–86.

[^3]: Meredith Whittaker, “The Steep Cost of Capture,” _Interactions_ 28, no. 6 (November 2021): 50–55, [https://doi.org/10.1145/3488666](https://doi.org/10.1145/3488666); Michele Banko and Eric Brill, “Scaling to Very Very Large Corpora for Natural Language Disambiguation,” in _Proceedings of the 39th Annual Meeting on Association for Computational Linguistics - ACL ’01_ (Toulouse, France: Association for Computational Linguistics, 2001), 26–33.

[^4]: Johan Schalkwyk et al., “Google Search by Voice: A Case Study,” 2010, 1–35, pg. 2.


## Published

- Dockray, Sean. “Always Listening: The World as a Wake Word.” _Conflict in my Outlook_. UQAM/ Perimeter Press, 2022.