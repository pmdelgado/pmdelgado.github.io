---
layout: page
title: Engineering
permalink: /engineering/
---

- I am currently Senior Scientist at the the Advanced Audio Research Group in Fraunhofer IIS, focusing on the new Moving Picture Experts Group **standard for audio for virtual and augmented reality (VR/AR)**, [MPEG-I](https://www.iis.fraunhofer.de/en/ff/amm/for/mpegi.html). The standard has now [reached International Standard status](https://www.mpeg.org/standards/MPEG-I/4/).
- Before that, I've spent some years on subjective and objective audio quality assessment for state-of-the-art perceptual audio codecs. During this time I've worked on extending an established ITU-R objective quality assessment method (BS.1387-1, PEAQ) for parametric codecs and multi-channel audio.
- Before that, as a part of the [Audio and Multimedia Technologies Division](https://www.iis.fraunhofer.de/en/ff/amm.html?f=cdk.pdf), I researched and designed audio processing algorithms for **embedded devices** and digital signal processors, maintaining and expanding the [Core Design Kit](https://www.iis.fraunhofer.de/content/dam/iis/de/doc/ame/wp/FraunhoferIIS_White-Paper_CDK.pdf). This involved collaboration with international partners such as [Google](https://www.iis.fraunhofer.de/content/dam/iis/en/doc/ame/pressreleases/FraunhoferIIS_Presseinformation_HE-AAC_Cingo_GooglePlay_24072013.pdf), [Apple, Amazon and others](https://www.iis.fraunhofer.de/en/profil/jb/2019/apple-amazon-android-with-xhe-aac.html), and [NHK Japan](https://www.audioblog.iis.fraunhofer.com/8k-broadcast). 
- I have been involved in the development, implementation, optimization, and testing of cross-platform audio coding software in line with **MPEG and 3GPP standards**, as well as the design and development of automated software tests and deployment planning.
- I've filed [patents](https://patents.google.com/?q=(Pablo+Delgado+fraunhofer)&oq=Pablo+Delgado+fraunhofer&dups=language)

# [MPEG‑I Immersive Audio](https://www.iis.fraunhofer.de/en/ff/amm/for/mpegi.html)

I was part of the core development team of the standard.

## Articles, interviews, press coverage and standard resources
- [MPEG-I Immersive Audio—The ISO/MPEG Standard for Virtual/Augmented Reality Audio](https://www.iis.fraunhofer.de/content/dam/iis/en/doc/ame/Whitepaper/mpeg-i/MPEG-I_Immersive_Audio%E2%80%94The_ISO_MPEG_Standard_for_Virtual_Augmented_Reality_Audio.pdf)
- [AudioXpress — MPEG‑I Immersive Audio: The Standard for Realistic VR/AR Sound](https://audioxpress.com/article/mpeg-i-immersive-audio-the-standard-for-realistic-vr-ar-sound)
- [MPEG — MPEG‑I Part 4: Immersive Audio](https://www.mpeg.org/standards/MPEG-I/4/)
- [Nokia — MPEG‑I Immersive Audio](https://www.nokia.com/multimedia/audio/technology-and-standards/mpeg-i-immersive-audio/)
- [Inavate — “Sound Source Delay” Technology Adopted into MPEG‑I Immersive Audio Standard](https://www.inavateonthenet.net/news/article/sound-source-delay-technology-adopted-into-mpegi-immersive-audio-standard)
- [TechRadar Pro — Unveiling MPEG‑I: The Next Generation of VR and AR Audio](https://www.techradar.com/pro/unveiling-mpeg-i-the-next-generation-of-vr-and-ar-audio)
- [Analog IC Tips — What Codecs Are There for Immersive and 3D Audio?](https://www.analogictips.com/what-codecs-are-there-for-immersive-and-3d-audio/)
- [Immersive Audio Podcast — Episode 93: Jürgen Herre and MPEG‑I](https://immersiveaudiopodcast.com/episode-93-juergen-herre-mpeg-i/)
- [ISO/IEC JTC 1/SC 29 — MPEG Showcases Groundbreaking Demonstrations of MPEG‑I Immersive Audio](https://committee.iso.org/sites/jtc1sc29/home/news/content-left-area/news-and-updates/news-2.html)

# [MPEG-H Personalized Immersive Sound](https://www.iis.fraunhofer.de/en/ff/amm/broadcast-streaming/mpegh.html)

I was part of the team that produced the first embedded MPEG-H audio encoder of Fraunhofer. In particular, I was in charge of the fixed-point architecture integration of the core audio encoder and audio quality testing.

## Articles, interviews, and standard resources

- [Ericsson Integrates Fraunhofer's MPEG-H TV Audio System Into Its Contribution-Encoder/Decoder Solution](https://www.iis.fraunhofer.de/en/pr/2018/20180409_MPEGH_Ericsson.html)


# [Delay-reduced mode of MPEG-4 Enhanced Low Delay AAC (AAC-ELD)](http://www.aes.org/events/140/presenters/?ID=4564)

The MPEG-4 AAC Enhanced Low Delay (AAC-ELD) coder is well established in high quality communication applications, such as Apple’s FaceTime, as well as in professional live broadcasting. Both applications require high interactivity, which typically demands an algorithmic codec delay between 15 ms and 35 ms. Recently, MPEG finalized a new delay-reduced mode for AAC-ELD featuring only a fraction of the regular algorithmic delay. This mode operates virtually at higher sampling rates while maintaining standard sampling rates for I/O. Supporting this feature, AAC-ELD can address even more delay critical applications, like wireless microphones or headsets for TV.  
In this paper, main details of the delay-reduced mode of AAC-ELD are presented and application scenarios are outlined. Audio quality aspects are discussed and compared against other codecs with a delay below 10 ms.

# Other Projects
- [Low Distortion Audio Power Amplifier, design and implementation.](http://pmdelgado.wordpress.com/2014/04/16/project-low-distortion-audio-power-amplifier-design-and-implementation/) A low distortion audio power amplifier I designed with discrete components. An analysis and justification of each stage is carried out and some performance measurements are shown.
- [A real time closed loop control system and target identification through Ethernet. Design and implementation.](http://pmdelgado.wordpress.com/2014/04/16/project-a-real-time-closed-loop-control-system-and-target-identification-through-ethernet-design-and-implementation/) Implementation of a closed loop control system on a PIC microcontroller for a direct current motor with parameters passed in real time through an Ethernet link.
- [Project: A Low Cost MIDI Fast Response Configurable Step Sequencer, design and implementation.](http://pmdelgado.wordpress.com/2014/04/16 project-a-low-cost-midi-fast-response-configurable-step-sequencer-design-and-implementation/) A MIDI based, low level, real time event sequencer with an 8051 microcontroller. This device has the capability of communicating with other external equipment which support this protocol and establishing a synchronized execution of diverse events on other equipment.
- [Project: An Adaptive NLMS Algorithm for a MVDR Beamformer, design and performance analysis.](http://pmdelgado.wordpress.com/2014/04/16/project-an-adaptive-nlms-algorithm-for-a-mvdr-beamformer-design-and-performance-analysis/) A Normalized Least Mean Squares adaptive filter algorithm for an antenna array. Real time performance analysis for a QPSK modulated, 1 GHz carrier received test signal.
- [Project: PLL Based Effects Processor, product design and implementation.](http://pmdelgado.wordpress.com/2014/04/16/project-pll-based-effects-processor-product-design-and-implementation/) I designed a sound effect processor (signal modulator) based on a PLL 4046 circuit and an envelope follower.
