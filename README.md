# <p align=center> This repo supplements our survey: Unveiling Musical Emotions: Exploring the Landscape of Music Emotion Recognition

Authors: [Jaeyong Kang](https://scholar.google.com/citations?user=kEI6KkIAAAAJ&hl=en), [Dorien Herremans](https://scholar.google.com/citations?user=Hp5W5f0AAAAJ&hl=en)
</p>

> **<p align="justify"> Abstract:** *This paper presents a novel perspective on Music Emotion Recognition (MER), focusing on distinct challenges, community engagement, and innovative approaches. Rather than striving for comprehensive coverage within the confines of traditional surveys, we delve into the dynamic landscape of MER, emphasizing collaborative efforts, emerging challenges, and promising avenues for research. Our exploration offers insights into the evolving methodologies and applications within the field, aiming to inspire dialogue and collaboration among researchers and practitioners. By embracing a nuanced perspective and highlighting unique angles, this paper contributes to the ongoing discourse on MER, paving the way for future advancements and collaborative endeavors.* </p>

A curated list of Datasets and Models for Music Emotion Recognition (MER)

## Overview
- [Datasets](#datasets)
- [Models](#models)

## Dataset

| Dataset                             | Year | # of instances | Length  | Type          | Categorical | Dimensional | Dynamic | Induced  |
|-------------------------------------|------|----------------|---------|---------------|-------------|-------------|---------|----------|
| MoodsMIREX                          | 2007 | 269            | 30s     | MP3           | 5 labels    | -           | Static  | Perceived|
| CAL500                              | 2007 | 500            | full    | MP3           | 174 labels  | -           | Static  | Perceived|
| Yang-Dim                            | 2008 | 195            | 25s     | WAV           | -           | Russell     | Static  | Perceived|
| MoodSwings                          | 2008 | 240            | 15s     | MP3           | -           | Russell     | Dynamic | Perceived|
| NTWICM                              | 2010 | 2,648          | full    | MP3           | -           | Russell     | Static  | Perceived|
| Eerola et al.'s dataset             | 2011 | 470            | 15s-1m  | MP3           | 6 labels    | 3 dimensions| Static  | Perceived|
| MoodSwings Turk                     | 2011 | 240            | 15s     | MP3           | -           | Russell     | Dynamic | Perceived|
| DEAP                                | 2012 | 120            | 60s     | YouTube id    | -           | Russell     | Static  | Induced  |
| Panda et al.'s dataset              | 2013 | 903            | 30s     | MP3, MIDI     | 21 labels   | -           | Static  | Perceived|
| Solymani et al.'s dataset           | 2013 | 1000           | 45s     | MP3           | -           | Russell     | Both    | Perceived|
| CAL500exp                           | 2014 | 3,223          | 3s-16s  | MP3           | 67 labels   | -           | Static  | Perceived|
| AMG1608                             | 2015 | 1,608          | 30s     | WAV           | -           | Russell     | Static  | Perceived|
| Emotify                             | 2016 | 400            | 60s     | MP3           | GEMS        | -           | Static  | Induced  |
| Moodo                               | 2016 | 200            | 15s     | WAV           | -           | Russell     | Static  | Perceived|
| Malheiro et al.'s dataset           | 2016 | 200            | 30s     | Audio, Lyrics | Quadrants   | -           | Static  | Perceived|
| CH818                               | 2017 | 818            | 30s     | MP3           | -           | Russell     | Static  | Perceived|
| 4Q-emotion                          | 2018 | 900            | 30s     | MP3           | Quadrants   | -           | Static  | Perceived|
| MediaEval DEAM                      | 2018 | 2,058          | 45s     | MP3           | -           | Russell     | Both    | Perceived|
| PMEmo                               | 2018 | 794            | full    | MP3           | -           | Russell     | Both    | Induced  |
| RAVDESS                             | 2018 | 1,012          | full    | MP3, MP4      | 5 labels    | -           | Static  | Perceived|
| DMDD                                | 2018 | 18,644         | full    | Audio, Lyrics | -           | Russell     | Static  | Perceived|
| MTG-Jamendo                         | 2019 | 18,486         | full    | MP3           | 56 labels   | -           | Static  | Perceived|
| VGMIDI                              | 2019 | 200            | full    | MIDI          | -           | Russell     | Dynamic | Perceived|
| Turkish Music Emotion               | 2019 | 400            | 30s     | MP3           | 4 labels    | -           | Static  | Perceived|
| EMOPIA                              | 2021 | 1,087          | 30s-40s | Audio, MIDI   | Quadrants   | -           | Static  | Perceived|
| MER500                              | 2020 | 494            | 10s     | WAV           | 5 labels    | -           | Static  | Perceived|
| Music4all                           | 2020 | 109,269        | 30s     | WAV           | -           | 3 dimensions| Static  | Perceived|
| CCMED-WCMED                         | 2020 | 800            | 8-20s   | WAV           | -           | Russell     | Static  | Perceived|
| MuSe                                | 2021 | 90,001         | full    | Audio         | -           | Russell (V-A-D)| Static | Perceived|
| HKU956                              | 2022 | 956            | full    | MP3           | -           | Russell     | Static  | Induced  |
| MERP                                | 2022 | 54             | full    | WAV           | -           | Russell     | Both    | Perceived|
| MuVi                                | 2022 | 81             | full    | YouTube id    | GEMS        | Russell     | Both    | Perceived|
| YM2413-MDB                          | 2022 | 699            | full    | WAV, MIDI     | 35 labels   | -           | Static  | Perceived|
| MusAV                               | 2022 | 2,092          | full    | WAV           | -           | Russell     | Static  | Perceived|
| EmoMV                               | 2023 | 5,986          | 30s     | WAV           | 6 labels    | -           | Static  | Perceived|
| Indonesian Song                     | 2023 | 476            | full    | WAV           | 3 labels    | -           | Static  | Perceived|
| TROMPA-MER                          | 2023 | 1,161          | 30s     | WAV           | 11 labels   | -           | Static  | Perceived|
| Music-Mouv                          | 2023 | 188            | full    | Spotify id    | GEMS        | -           | Static  | Induced  |
| ENSA                                | 2023 | 60             | full    | MP3           | -           | Russell     | Dynamic | Perceived|
| EMMA                                | 2024 | 364            | 30s-60s | WAV           | GEMS        | -           | Static  | Perceived|
| SiTunes                             | 2024 | 300            | full    | WAV           | -           | Russell     | Static  | Induced  |
| MERGE                               | 2024 | 3,554          | full    | Audio, Lyrics | Quadrants   | -           | Static  | Perceived|

## Models

| Ref.                                     | Year | Modalities     | Approach                          | Emotion Model | Dataset                   |
|------------------------------------------|------|----------------|-----------------------------------|---------------|---------------------------|
| Music mood detection based on audio and lyrics with deep neural net | 2018 | Audio, Lyrics  | Bimodal CNN-LSTM                 | Russell       | MSD                       |
| Recognition of emotion in music based on deep convolutional neural network [Check paper for modality] | 2020 | Audio          | CNN, Local Attention             | 4 classes     | Soundtracks, Bi-Modal     |
| Emotion and theme recognition in music using attention-based methods | 2020 | Audio          | Attention Based Neural Networks  | 56 classes    | Jamendo                   |
| Regression-based Music Emotion Prediction using Triplet Neural Networks | 2020 | Audio          | Triplet Neural Networks           | Russell       | DEAM                      |
| Recognizing Song Mood and Theme: Clustering-based Ensembles | 2021 | Audio          | Clustering-based Ensembles        | 56 classes    | Jamendo                   |
| Semi-supervised music emotion recognition using noisy student training and harmonic pitch class profiles | 2021 | Audio          | Semi-Supervised, Noisy Student Training | 56 classes | Jamendo                   |
| Frequency Dependent Convolutions for Music Tagging | 2021 | Audio          | Frequency Dependent Convolutions  | 56 classes    | Jamendo                   |
| SELAB-HCMUS at MediaEval 2021: Music Theme and Emotion Classification with Co-teaching Training Strategy | 2021 | Audio          | Co-teaching Training Strategy    | 56 classes    | Jamendo                   |
| Music emotion recognition using recurrent neural networks and pretrained models | 2021 | Audio          | LSTM, Pretrained Models          | Russell       | Self-built                |
| Transformer-based approach towards music emotion recognition from lyrics | 2021 | Lyrics         | Transformers                     | Russell       | MoodyLyrics, MER          |
| Tracing back music emotion predictions to sound sources and intuitive perceptual qualities | 2021 | Audio          | Source-separation based explainer | Russell    | DEAM, Midlevel, PMEmo    |
| A generative adversarial network model based on intelligent data analytics for music emotion recognition under IoT | 2021 | Audio          | Generative Adversarial Network   | 2 classes     | Self-built                |
| Study on music emotion recognition based on the machine learning model clustering algorithm | 2022 | Audio          | Clustering Algorithm             | Russell       | MediaEval emotion in music|
| A novel multi-task learning method for symbolic music emotion recognition | 2022 | MIDI           | Multi-Task Learning               | 4 classes     | EMOPIA, VGMIDI            |
| Feature selection approaches for optimising music emotion recognition methods | 2022 | Audio          | Feature Selection                | Russell       | MediaEval DEAM            |
| Predicting emotion from music videos: exploring the relative contribution of visual and auditory information to affective responses | 2022 | Audio, Video   | LSTM                             | Russell       | Self-built                |
| MERGE Lyrics: Music Emotion Recognition next Generation--Lyrics Classification with Deep Learning | 2022 | Lyrics         | Deep Learning, BERT              | 4 classes     | MIR Lyrics Emotion        |
| Multi-Modality in Music: Predicting Emotion in Music from High-Level Audio Features and Lyrics | 2023 | Audio, Lyrics  | Multi-Modality                   | Russell       | DMDD                      |
| Music emotion recognition based on a neural network with an inception-gru residual structure | 2023 | Audio          | Neural Network with Inception-GRU Residual | 4 classes | Soundtracks              |
| Modeling emotion dynamics in song lyrics with state space models | 2023 | Lyrics         | State Space Models               | 6 classes     | LyricsEmotions            |
| Tollywood Emotions: Annotation of Valence-Arousal in Telugu Song Lyrics | 2023 | Lyrics         | Fine-tuned XLMRoBERTa           | Russell       | Self-built                |
| Multimodal music emotion recognition in Indonesian songs based on CNN-LSTM, XLNet transformers | 2023 | Audio, Lyrics  | CNN-LSTM, XLNet Transformers    | 3 classes     | Self-built                |
| Modularized composite attention network for continuous music emotion recognition | 2023 | Audio          | Attention Mechanism              | Russell       | DEAM, PMEmo               |
| Automatic music emotion classification model for movie soundtrack subtitling based on neuroscientific premises | 2023 | Audio          | CNN                             | 4 classes     | Musical Excerpts          |
| Transformer-based automatic music mood classification using multi-modal framework | 2023 | Audio, Lyrics  | Transformers                     | 4 classes     | MoodyLyrics               |

