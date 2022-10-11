# Video-SA-intro
Samples of Video-SA (Video Data for Multimodal Sentiment Analysis)

The dataset has 1350 videos (30s, 600x360, 30fps, and split into 10s each for usage), with 675 sentiment data and 675 neutral data. and is divided into two parts: major film and television dramas. This data set is mainly used for multi-modal sentiment analysis. Images, speech and text modalities can be extracted from each video. The sentiment label not only contains the basic 6 emotions: anger, disgust, fear, happiness, sadness, and surprise, but also includes complex emotions and advanced rhetoric including sarcasm, weeping with joy, self-deprecating, melancholic, worried, jealous, ashamed, metaphor (positive), metaphor (negative). 

The emotional samples in Video-SA are collected from two parts: 375 videos of 5 volunteers in 15 contexts (5 videos per context) and 300 videos of popular TV shows (20 videos per context). For the former, we designed 5 long dialogue scenes (30s, including text content, voice intonation and facial expressions) for each context according to the IEMOCAP and MUStARD datasets. 5 volunteers were filmed under natural light conditions. For the latter, we crawled 800 copyright-free videos from websites such as YouTube, and finally obtained 300 videos in 15 contexts. The samples of neutral emotion are collected through the same way.

![1665500207049](https://user-images.githubusercontent.com/45681444/195126276-4172d302-b2f1-4ba4-92c8-a0882ab78010.png)

Samples of this dataset will be upload before 2023.

V 2.0
For further work, we have also set up 180 negative samples in Video-SA (i.e., for each basic emotion, 30 samples that their facial expressions, text and audio messages do not belong to the sentiment category in which they are located, e.g., facial anchor does not correspond to the target) to facilitate future exploration of comparison learning, and all of them will be supplemented in subsequent dataset version updates.
