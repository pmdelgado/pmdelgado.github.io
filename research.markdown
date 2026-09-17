---
layout: page
title: Research
permalink: /research/
---

**Profiles:** [Google Scholar](https://scholar.google.com/citations?user=N94T9OkAAAAJ&hl=en) · [Teaching](https://www.audiolabs-erlangen.de/fraunhofer/assistant/delgado)

## Publications

- **[Comparing Training Objectives for Neural Post-Filtering of Coded Music](https://iwaenc2026.org/program/poster_78.html)**  
  *IWAENC, 2026*

  *Authors:* Heinmüller, Alexander; Brendel, Andreas; Delgado, Pablo M.; Herre Jürgen.

  <details>
  <summary>Abstract</summary>

  Neural post-filters are an effective tool for improving the reconstruction quality of audio codecs, and hence, numerous models have been proposed in the literature. In this work, we compare several training paradigms—discriminative training, generative adversarial networks (GANs), score-based diffusion (SD), and conditional flow matching—for post-filtering speech and music, and we evaluate the resulting quality improvements across different perceptual audio codecs. We show that GANs can achieve music quality similar to that of SD models at a fraction of the computational complexity. Since the characteristics of a music signal are relevant for the performance of a codec, we further investigate how neural post-filters behave across different signal types.

  </details>

- **[MPEG-I Immersive Audio—The ISO/MPEG Standard for Virtual/Augmented Reality Audio](https://aes.org/publications/elibrary-page/?id=23235)**  
  *Journal of the Audio Engineering Society, 2026*

  *Authors:* Disch, Sascha; Terentiv, Leon; Koppens, Jeroen; Falk, Tommy; Leppänen, Jussi; Munoz, Isaac; Herre, Jürgen; Adami, Alexander; Silzle, Andreas; Fischer, Daniel; Setiawan, Panji; Fersch, Christof; Hanschke, Jan-Hendrik; Jelfs, Sam; de Bruijn, Werner; Eronen, Antti; Mate, Sujeet; Dick, Sascha; Borss, Christian; Delgado, Pablo M.; Trinidad, Miguel M.

  <details>
  <summary>Abstract</summary>

  The ISO/MPEG international standard on MPEG-I immersive audio was issued in November 2025 by the MPEG Audio group (ISO/IEC JTC 1/SC 29/WG 6). It provides technology for a compressed audio representation and real-time interactive rendering within virtual and augmented reality applications with six degrees of freedom. It enables efficient bitrate management, high-quality storage, and transmission of virtual environments, including audio sources with spatial dimensions and specific radiation traits, such as musical instruments, along with geometric descriptions of acoustically relevant scene details, including walls, doors, sound-reflecting, and occluding elements.

  The audio rendering process incorporates comprehensive modeling of room acoustics and intricate acoustic phenomena, including occlusion, reflection, and diffraction caused by sound obstacles, the Doppler effect, and dynamic environment changes triggered by user interactivity. This article presents an overview of the background, development, underlying technology, and selected application aspects of the new standard.

  </details>

- **[DeepAQ: A Perceptual Audio Quality Metric Based on Foundational Models and Weakly Supervised Learning](https://ieeexplore.ieee.org/abstract/document/11465130)**  
  *ICASSP, 2026*

  *Authors:* Jiang, Guanxin and co-authors.

  <details>
  <summary>Abstract</summary>

  This paper presents the Deep learning-based Perceptual Audio Quality metric (DeepAQ) for evaluating general audio quality. The approach leverages metric learning together with the music foundation model MERT, guided by surrogate labels, to construct an embedding space that captures distortion intensity in general audio.

  To the best of our knowledge, DeepAQ is the first general-audio-quality method to leverage weakly supervised labels and metric learning for fine-tuning a music foundation model with Low-Rank Adaptation (LoRA). We benchmark the proposed model against state-of-the-art objective audio quality metrics across listening tests spanning audio coding and source separation. Results show that the method surpasses existing metrics in detecting coding artifacts and generalizes well to unseen distortions such as source separation.

  </details>

- **[Exploring Perceptual Audio Quality Measurement on Stereo Processing using the Open Dataset of Audio Quality](https://aes2.org/publications/elibrary-page/?id=23040)**  
  *Audio Engineering Society Convention, Long Beach, CA, 2025*

  *Authors:* Sascha Dick, Mhd Modar Halimeh, Chih-Wei Wu, Christoph Thompson, Phillip A. Williams, and Pablo M. Delgado.

  <details>
  <summary>Abstract</summary>

  ODAQ (Open Dataset of Audio Quality) provides a comprehensive framework for exploring monaural and binaural audio quality degradations across a range of distortion classes and signals, accompanied by subjective quality ratings.

  Recent updates provide test signals and listener ratings where artifacts may occur in both stereo channels or in a single channel, using established coding methods such as Mid/Side (M/S) and Left/Right (L/R). These cases provide a useful resource for investigating timbre and spatial-audio quality perception through auditory models included in objective audio quality metrics.

  </details>

- **[Investigating the Impact of Stereo Processing—A Study for Extending the Open Dataset of Audio Quality](https://aes2.org/publications/elibrary-page/?id=23039)**  
  *Audio Engineering Society Convention, Long Beach, CA, 2025*

  *Authors:* Sascha Dick, Chih-Wei Wu, Christoph Thompson, Phillip A. Williams, and Matteo Torcoli.

  <details>
  <summary>Abstract</summary>

  The Open Dataset of Audio Quality (ODAQ) addresses the scarcity of available audio material with different signal impairments and associated subjective scores, focusing primarily on monaural artifacts and changes in timbre.

  This paper presents an initial study for extending ODAQ toward stereo processing and binaural hearing. Monaural artifacts were combined with Left/Right (LR) and Mid/Side (MS) stereo preprocessing across diverse stereo characteristics, including monaural recordings and hard-panned mixes.

  MUSHRA listening-test results indicate that the preference for LR or MS coding is substantially influenced by the stereo characteristics of the test signal. The findings also show that differences between LR and MS are significantly affected by presentation context. Listeners primarily assess timbral impairments when spatial characteristics are consistent and focus on stereo-image issues when timbral quality is similar.

  </details>

- **Panel Discussion: Neural Audio Coding Techniques and Their Evaluation**  
  *Audio Engineering Society Artificial Intelligence and Machine Learning for Audio Conference, London, 8–10 September 2025*

  *Participants:* Jan Skoglund, Jürgen Herre, Julian Parker, and Stéphane Ragot.

  <details>
  <summary>Description</summary>

  Neural audio coding is a cutting-edge approach to audio compression, but its technology development is still in its infancy. This panel presented an overview of neural audio coding techniques in development and highlighted dataset robustness issues.

  The discussion emphasized the need for robust subjective and objective evaluation methods, given that neural codecs may generate outputs that differ substantially from the original signal. It also explored which established assessment principles remain relevant and how insights from generative models can inform new evaluation strategies.

  </details>

- **[Towards Improved Objective Perceptual Audio Quality Assessment—Part 1: A Novel Data-Driven Cognitive Model](https://ieeexplore.ieee.org/abstract/document/10711267)**  
  *IEEE/ACM Transactions on Audio, Speech, and Language Processing*

  <details>
  <summary>Abstract</summary>

  Efficient audio-quality assessment is vital for streamlining audio-codec development. Objective assessment tools have been developed to predict subjective audio-quality ratings algorithmically, thereby reducing the need for extensive listening tests.

  This two-part work proposes extensions to the Perceptual Evaluation of Audio Quality (PEAQ), specified in ITU-R BS.1387-1. Part 1 focuses on improving generalization, while Part 2 addresses accurate spatial-audio-quality measurement.

  Part 1 introduces a machine-learning approach that uses subjective data to model cognitive aspects of audio-quality perception. The proposed model adaptively weights different distortion metrics according to their perceived severity and cognitive salience. Compared with existing machine-learning methods and established tools, the proposed architecture achieves higher prediction accuracy on previously unseen subjective-quality data.

  </details>

- **[Expanding and Analyzing ODAQ—The Open Dataset of Audio Quality](https://aes2.org/publications/elibrary-page/?id=22721)**  
  *157th Audio Engineering Society Convention, New York City, 2024*

  <details>
  <summary>Abstract</summary>

  The Open Dataset of Audio Quality (ODAQ) was introduced to address the scarcity of openly available audio datasets with corresponding subjective-quality scores. The dataset comprises audio material processed using six different signal-processing methods at five quality levels, together with subjective-test results.

  This work expanded the dataset through additional listening tests conducted by university students following listener training. The results were consistent with those from expert listeners. The expanded dataset contains results from three international laboratories, 42 listeners, and 10,080 subjective scores.

  </details>

- **Workshop: Applications of Artificial Intelligence and Machine Learning in Audio Quality Models**  
  *156th and 157th Audio Engineering Society Conventions, Madrid and New York City, 2024*

  *Co-organizers:* Jan Skoglund, Phillip Williams, Arijit Biswas, and Hannes Gamper.

  <details>
  <summary>Description</summary>

  This workshop, sponsored by the AES Technical Committee on Machine Learning and Artificial Intelligence, provided hands-on experience with machine learning for audio-quality modeling.

  Topics included experimental design, data collection, data augmentation, filtering, model design, and cross-validation. The workshop also covered historical and modern approaches to combining machine learning with auditory perception and provided participants with tools for evaluating ML-based quality models.

  </details>

- **[Design Choices in a Binaural Perceptual Model for Improved Objective Spatial Audio Quality Assessment](https://scholar.google.com/scholar?oi=bibs&cluster=17853319656859091150&btnI=1&hl=en)**  
  *Audio Engineering Society Convention, 2023*

  <details>
  <summary>Abstract</summary>

  Spatial-audio-quality assessment is crucial for immersive user experiences, but subjective evaluations are time-consuming and costly. This study focuses on developing an improved binaural perceptual model for spatial-audio-quality measurement by selecting the best-performing design parameters from previously proposed methods.

  Existing binaural models, particularly extensions of the Perceptual Evaluation of Audio Quality (PEAQ), are investigated to enhance spatial-audio-quality metrics.

  </details>

- **[An Improved Metric of Informational Masking for Perceptual Audio Quality Measurement](https://arxiv.org/abs/2307.06656)**  
  *WASPAA, 2023*  
  [Video and slides](https://sigport.org/documents/improved-metric-informational-masking-perceptual-audio-quality-measurement)

  <details>
  <summary>Abstract</summary>

  This paper presents an improved model of informational masking, an important cognitive effect in audio-quality perception. The model considers disturbance-information complexity around the masking threshold.

  The proposed metric is incorporated into a perceptual audio-quality measurement system using a novel interaction-analysis procedure between cognitive effects and distortion metrics. Validation against large and diverse listening-test databases shows that the proposed metric outperforms previously proposed informational-masking metrics.

  </details>

- **[Objective Quality Assessment of Perceptually Coded Audio Signals](https://opus4.kobv.de/opus4-fau/files/22761/DissertationPabloDelgado_electronic_no_logo.pdf)**  
  *Doctoral dissertation*  
  [Presentation](https://www.youtube.com/watch?v=hfDfuHvjxCE)

  <details>
  <summary>Abstract</summary>

  The main goal of audio-signal coding and processing is to achieve the best possible sound quality within specific parameters. Perceptual audio-coding algorithms eliminate redundant and irrelevant information, but can also produce artifacts that degrade sound quality.

  This thesis proposes contributions to improve both timbral and spatial aspects of objective audio-quality assessment by extending perceptual models of human hearing.

  </details>

- **[A Data-Driven Cognitive Salience Model for Objective Audio Quality Assessment](https://ieeexplore.ieee.org/document/9747064?dld=)**  
  *ICASSP, 2022*  
  [Video and slides](https://sigport.org/documents/data-driven-cognitive-salience-model-objective-perceptual-audio-quality-assessment-0)

  <details>
  <summary>Abstract</summary>

  This work proposes a data-driven salience model for objective audio-quality measurement. The model estimates interactions between cognitive effects and degradation metrics and uses these interactions to improve the prediction of subjective-quality scores.

  Systems incorporating the proposed salience model outperform equivalent systems that use only statistical learning to combine cognitive and degradation metrics.

  </details>

- **[Can We Still Use PEAQ? A Performance Analysis of the ITU Standard for the Objective Assessment of Perceived Audio Quality](https://ieeexplore.ieee.org/document/9123105)**  
  [Video](https://www.youtube.com/watch?v=6fo-mp7_SCU&feature=youtu.be) · [arXiv](http://arxiv.org/abs/2212.01467)

  <details>
  <summary>Abstract</summary>

  The Perceptual Evaluation of Audio Quality (PEAQ), described in ITU-R BS.1387, is widely used to estimate the quality of perceptually coded audio signals. However, its limitations are particularly evident for newer technologies such as bandwidth extension and parametric multichannel coding.

  The results indicate that PEAQ's disturbance-loudness model remains competitive, although its performance depends on signal type. An updated mapping of Model Output Values to the Distortion Index can substantially improve performance. The paper also provides recommendations for improving PEAQ.

  </details>

- **Invited Workshop: To PEAQ or Not to PEAQ?—BS.1387 Revisited**  
  *147th Audio Engineering Society Convention*

  *Speakers:* Pablo Delgado and Thomas Sporer.  
  [Workshop information](http://www.aes.org/events/147/acousticssessions/?ID=6885)

  <details>
  <summary>Description</summary>

  This workshop examined the ITU-R BS.1387 recommendation for assessing bit-reduced audio signals. It explained how PEAQ was designed and validated, demonstrated cases where it fails to predict perceived quality, summarized subsequent work involving newer audio-coding tools and spatial audio, and discussed possible future developments.

  </details>

- **[Objective Measurement of Stereophonic Audio Quality in the Directional Loudness Domain](http://www.aes.org/e-lib/browse.cfm?elib=20624)**

  <details>
  <summary>Abstract</summary>

  This paper proposes a scene-analysis method that considers signal loudness distributed across estimated source directions on the horizontal plane. Distortion features are calculated in the directional-loudness domain rather than the conventional time-frequency domain.

  Experiments using an extensive database of parametric-audio-codec listening tests show that the proposed features provide equal or better correlation with subjectively perceived quality degradation than previous methods.

  </details>

- **[Influence of Binaural Processing on Objective Perceptual Quality Assessment](http://www.aes.org/e-lib/browse.cfm?elib=20505)**

  <details>
  <summary>Abstract</summary>

  This paper investigates how variations in binaural processing—including head rotations, added reverberation, and simulated room properties—affect the prediction performance of a standardized objective audio-quality measurement scheme based on PEAQ and extended to include spatial aspects.

  </details>

- **[Objective Assessment of Spatial Audio Quality Using Directional Loudness Maps](https://ieeexplore.ieee.org/document/8683810)**  
  [arXiv](http://arxiv.org/abs/2212.01451)

  <details>
  <summary>Abstract</summary>

  This work introduces a feature for representing perceived quality degradation in processed spatial-audio scenes. The feature is extracted from stereophonic or binaural signals using a simplified stereo model with auditory events positioned at different directions in the stereo field.

  The proposed directional-loudness distortion measure improves the prediction of subjective quality scores for spatially coded audio signals, including signals processed using bandwidth extension and joint-stereo coding.

  </details>

- **[Investigations on the Influence of Combined Inter-Aural Cue Distortions in Overall Audio Quality](https://www.dega-akustik.de/publikationen/online-proceedings/)**  
  [arXiv](http://arxiv.org/abs/2212.01427)

  <details>
  <summary>Abstract</summary>

  This work investigates how combinations of spatial distortions affect overall perceived audio quality. The study focuses on Inter-aural Level Difference Distortions, Inter-aural Time Difference Distortions, and Inter-aural Cross-correlation Distortions.

  Controlled combinations of spatial distortions were applied to representative audio signals and evaluated through listening tests. The results provide guidelines for designing distortion measures that account for interactions between spatial cues.

  </details>

- **[Energy-Aware Modeling of Inter-Channel Level Difference Distortion Impact on Spatial Audio Perception](http://www.aes.org/e-lib/browse.cfm?elib=19634)**

  <details>
  <summary>Abstract</summary>

  This paper proposes an energy-aware model of Inter-aural Level Difference Distortion perception. The model accounts for the dependency of perceived distortion on the energy content of different spectral regions.

  Model parameters were fitted to subjective listening-test results and compared with existing approaches using databases of real coded signals.

  </details>

## Other projects

- **[An Expressive Multidimensional Physical Modelling Percussion Instrument](http://vbn.aau.dk/en/publications/an-expressive-multidimensional-physical-modelling-percussion-instrument(e0e138ac-1ab5-4954-a829-dd95a6bfece3).html)**  
  *Proceedings of the 15th Sound and Music Computing Conference, 2018*  
  [ResearchGate](https://www.researchgate.net/publication/332268472_An_Expressive_Multidimensional_Physical_Modelling_Percussion_Instrument) · [Demo 1](https://youtu.be/6NMmVBBbhzg) · [Demo 2](https://www.youtube.com/watch?v=X4KBgh0xO_0)

  I provided the ground concept and code. The project was developed with the Multisensory Experience Laboratory of the University of Aalborg.

  <details>
  <summary>Description</summary>

  This paper describes the design, implementation, and evaluation of a digital percussion instrument with multidimensional polyphonic control of a real-time physical-modeling system.

  The system uses modular parametric control of physical models, excitations, and couplings, together with continuous morphing and interaction capabilities. The evaluation showed that advances in sensor technology can enhance creativity in percussive instruments and extend gestural manipulation, but require carefully designed mapping schemes.

  </details>

- **[On the Effect of Inter-Channel Level Difference Distortions on the Perceived Subjective Quality of Stereo Signals](http://www.aes.org/e-lib/browse.cfm?elib=19441)**

  <details>
  <summary>Abstract</summary>

  Perceptual audio coding at low bitrates and stereo-enhancement algorithms can affect the perceived quality of stereo audio signals. In addition to changes in timbre, the spatial sound image may also be altered.

  This paper presents a study quantifying the effect of Inter-Channel Level Difference errors on perceived audio quality. The results show that larger errors lead to greater quality degradation and that spectral regions with relatively higher energy are affected more strongly.

  </details>

- **[Complexity Scaling of Audio Algorithms: Parametrizing the MPEG Advanced Audio Coding Rate-Distortion Loop](http://dafx16.vutbr.cz/dafxpapers/33-DAFx-16_paper_12-PN.pdf)**  
  *DAFx, 2016*

  <details>
  <summary>Abstract</summary>

  This paper proposes a modification to the rate-distortion loop in the quantization and coding stage of a fixed-point Advanced Audio Coding encoder. The modification introduces complexity scaling to control the trade-off between rate, distortion, and computational complexity.

  Results show that the framework can reduce up to 80% of the additional workload caused by the rate-distortion loop while remaining perceptually equivalent to the full-complexity version.

  </details>

- **[Acoustic Source Localization Using Wireless Sensor Networks](http://pmdelgado.wordpress.com/2014/04/21/research-acoustic-source-localization-using-wireless-sensor-networks/)**

  I developed an adaptive version of an algorithm for collaborative, distributed acoustic localization using energy readings from resource-constrained wireless sensor networks. Under certain conditions, the method outperforms commonly used approaches for a given set of design constraints.

## Talks and teaching

- **[Current Advances in Objective Quality Assessment of Perceptually Coded Audio Signals](https://uol.de/en/sfb-1330-hearing-acoustics/colloquium)**  
  *Invited talk, University of Oldenburg, Collaborative Research Centre SFB 1330, 2 December 2025*

  <details>
  <summary>Description</summary>

  The presentation focused on objective methods for predicting subjective audio-quality scores for perceptually coded signals. It covered recent advances in both timbral and spatial audio-quality measurement, including PEAQ-CSM and Directional Loudness Maps.

  </details>