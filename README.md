# <p align=center> This repo supplements our survey: Unveiling Musical Emotions: Exploring the Landscape of Music Emotion Recognition

Authors: [Jaeyong Kang](https://scholar.google.com/citations?user=kEI6KkIAAAAJ&hl=en), [Dorien Herremans](https://scholar.google.com/citations?user=Hp5W5f0AAAAJ&hl=en)
</p>

> **<p align="justify"> Abstract:** *This paper presents a novel perspective on Music Emotion Recognition (MER), focusing on distinct challenges, community engagement, and innovative approaches. Rather than striving for comprehensive coverage within the confines of traditional surveys, we delve into the dynamic landscape of MER, emphasizing collaborative efforts, emerging challenges, and promising avenues for research. Our exploration offers insights into the evolving methodologies and applications within the field, aiming to inspire dialogue and collaboration among researchers and practitioners. By embracing a nuanced perspective and highlighting unique angles, this paper contributes to the ongoing discourse on MER, paving the way for future advancements and collaborative endeavors.* </p>

A curated list of Datasets and Models for Music Emotion Recognition (MER)

## Overview
- [Datasets](#datasets)
- [Models](#models)

## Dataset

| Dataset                            | Year | # of instances | Length | Type       | Categorical | Dimensional | Dynamic | Induced  |
|-----------------------------------|------|----------------|--------|------------|-------------|-------------|---------|----------|
| MoodsMIREX                        | 2007 | 269            | 30s    | MP3        | 5 labels    | -           | Static  | Perceived|
| CAL500                            | 2007 | 500            | full   | MP3        | 174 labels  | -           | Static  | Perceived|
| Yang-Dim                          | 2008 | 195            | 25s    | WAV        | -           | Russell     | Static  | Perceived|
| MoodSwings                        | 2008 | 240            | 15s    | MP3        | -           | Russell     | Dynamic | Perceived|
| NTWICM                            | 2010 | 2,648          | full   | MP3        | -           | Russell     | Static  | Perceived|
| Soundtracks                       | 2011 | 470            | 15s-1m | MP3        | 6 labels    | 3 dimemsions| Static  | Perceived|
| DEAP                              | 2012 | 120            | 60s    | YouTube id | -           | Russell     | Static  | Induced  |
| Panda et al.'s dataset            | 2013 | 903            | 30s    | MP3, MIDI  | 21 labels   | -           | Static  | Perceived|
| Solymani et al.'s dataset         | 2013 | 1000           | 45s    | MP3        | -           | Russell     | Both    | Perceived|
| Emotify                           | 2016 | 400            | 60s    | MP3        | GEMS        | -           | Static  | Induced  |
| Moodo                             | 2016 | 200            | 15s    | WAV        | -           | Russell     | Static  | Perceived|
| CH818                             | 2017 | 818            | 30s    | MP3        | -           | Russell     | Static  | Perceived|
| 4Q-emotion                        | 2018 | 900            | 30s    | MP3        | Quadrants   | -           | Static  | Perceived|
| MediaEval DEAM                    | 2018 | 2,058          | 45s    | MP3        | -           | Russell     | Both    | Perceived|
| PMEmo                             | 2018 | 794            | full   | MP3        | -           | Russell     | Both    | Induced  |
| RAVDESS                           | 2018 | 1,012          | full   | MP3, MP4   | 5 labels    | -           | Static  | Perceived|
| DMDD                              | 2018 | 18,644         | full   | Audio, Lyrics | -         | Russell     | Static  | Perceived|
| MTG-Jamendo                       | 2019 | 18,486         | full   | MP3        | 56 labels  | -           | Static  | Perceived|
| VGMIDI                            | 2019 | 200            | full   | MIDI       | -           | Russell     | Dynamic | Perceived|
| Turkish Music Emotion             | 2019 | 400            | 30s    | MP3        | 4 labels    | -           | Static  | Perceived|
| EMOPIA                            | 2021 | 1,087          | 30s-40s| Audio, MIDI| Quadrants   | -           | Static  | Perceived|
| MER500                            | 2020 | 494            | 10s    | WAV        | 5 labels    | -           | Static  | Perceived|
| Music4all                         | 2020 | 109,269        | 30s    | WAV        | -           | 3 dimensions| Static  | Perceived|
| CCMED-WCMED                       | 2020 | 800            | 8-20s  | WAV        | -           | Russell     | Static  | Perceived|
| MuSe                              | 2021 | 90,001         | full   | Audio      | -           | Russell (V-A-D) | Static | Perceived|
| HKU956                            | 2022 | 956            | full   | MP3        | -           | Russell     | Static  | Induced  |
| MERP                              | 2022 | 54             | full   | WAV        | -           | Russell     | Both    | Perceived|
| MuVi                              | 2022 | 81             | full   | YouTube id | GEMS        | Russell     | Both    | Perceived|
| YM2413-MDB                        | 2022 | 699            | full   | WAV, MIDI  | 35 labels   | -           | Static  | Perceived|
| MusAV                             | 2022 | 2,092          | full   | WAV        | -           | Russell     | Static  | Perceived|
| EmoMV                             | 2023 | 5,986          | 30s    | WAV        | 6 labels    | -           | Static  | Perceived|
| Indonesian Song                   | 2023 | 476            | full   | WAV        | 3 labels    | -           | Static  | Perceived|
| TROMPA-MER                        | 2023 | 1,161          | 30s    | WAV        | 11 labels   | -           | Static  | Perceived|
| EMMA                              | 2024 | 364            | 30s-60s| WAV        | GEMS        | -           | Static  | Perceived|
| SiTunes                           | 2024 | 300            | full   | WAV        | -           | Russell     | Static  | Induced  |


## Models
| Paper | Year | Feature Modalities | Approach | Emotion Model | Dataset |
|-------|------|--------------------|----------|---------------|---------|
| Recognizing Song Mood and Theme: Clustering-based Ensembles | 2021 | audio | Clustering-based Ensembles | 56 classes | Jamendo |
| Semi-Supervised Music Emotion Recognition using Noisy Student Training and Harmonic Pitch Class Profiles | 2021 | audio | Semi-Supervised, Noisy Student Training, Harmonic Pitch Class Profiles | 56 classes | Jamendo |
| Frequency Dependent Convolutions for Music Tagging | 2021 | audio | Frequency Dependent Convolutions | 56 classes | Jamendo |
| SELAB-HCMUS at MediaEval 2021: Music Theme and Emotion Classification with Co-teaching Training Strategy | 2021 | audio | Co-teaching Training Strategy | 56 classes | Jamendo |
| Music Emotion Recognition using Recurrent Neural Networks and Pretrained Models | 2021 | - | Recurrent Neural Networks, Pretrained Models | - | - |
| Study on Music Emotion Recognition Based on the Machine Learning Model Clustering Algorithm | 2022 | - | Machine Learning Model Clustering Algorithm | - | - |
| Tracing Back Music Predictions to Sound Sources and Intuitive Perceptual Qualities | 2021 | - | - | - | - |
| Music Mood Detection Based On Audio And Lyrics With Deep Neural Net | 2018 | Audio, Lyrics | Deep Neural Net | - | - |
| Transformer-based approach towards music emotion recognition from lyrics | 2021 | Lyrics | Transformer-based | - | - |
| Semi-supervised music emotion recognition using noisy student training and harmonic pitch class profiles | 2021 | Harmonic Pitch Class Profiles | Noisy Student Training | - | - |
| Multi-Modality in Music: Predicting Emotion in Music from High-Level Audio Features and Lyrics | 2023 | Audio, Lyrics | Multi-Modality | - | - |
| Music Emotion Recognition Based on a Neural Network with an Inception-GRU Residual Structure | 2023 | - | Neural Network with Inception-GRU Residual Structure | - | - |
| A Novel Multi-Task Learning Method for Symbolic Music Emotion Recognition | 2022 | - | Multi-Task Learning | - | - |
| Feature Selection Approaches for Optimising Music Emotion Recognition Methods | 2022 | - | Feature Selection | - | - |
| Modelling Emotion Dynamics in Song Lyrics with State Space Models | 2022 | Lyrics | State Space Models | - | - |
| Fine-tuned XLMRoBERTa for Music Emotion Recognition in Telugu Songs | 2023 | - | Fine-tuned XLMRoBERTa | - | - |
| Deep Learning for Music Emotion Recognition: A Survey | 2020 | - | Deep Learning | - | - |
| Convolutional Neural Networks with Local Attention for Music Emotion Recognition | 2020 | - | Convolutional Neural Networks, Local Attention | - | - |
| Emotion Recognition from Music and Lyrics: A Deep Learning Approach | 2019 | Audio, Lyrics | Deep Learning | - | - |
| A Survey on Multimodal Music Emotion Recognition | 2020 | Audio, Lyrics | Multimodal | - | - |
| Context-Aware Music Emotion Recognition Using Attention Based Neural Networks | 2020 | - | Attention Based Neural Networks | - | - |
| Personalization of Music Emotion Recognition: A User-Adaptive Deep Learning Approach | 2021 | - | User-Adaptive Deep Learning | - | - |
| Towards Explainable Music Emotion Recognition: A Case Study with Transformers | 2022 | - | Transformers | - | - |
| Explainable Music Emotion Recognition with Attention-Based Capsule Networks | 2023 | - | Attention-Based Capsule Networks | - | - |
| Music Emotion Recognition for More Than Basic Emotions | 2020 | - | - | More Than Basic Emotions | - |
| Dimensional Music Emotion Recognition with a Multi-Task Learning Approach | 2022 | - | Multi-Task Learning | Dimensional | - |
| Music Emotion Recognition with Self-Attention Based Capsule Networks | 2022 | - | Self-Attention Based Capsule Networks | - | - |
| A Generative Adversarial Network Approach for Learning Emotion Representations from Music Audio | 2020 | - | Generative Adversarial Network | - | - |
| Music Emotion Transfer with Conditional Variational Autoencoders | 2021 | - | Conditional Variational Autoencoders | - | - |
| Musical Genre Aware Music Emotion Recognition with Attention Mechanism | 2022 | - | Attention Mechanism | - | - |
| Music Emotion Recognition in Social Media Videos | 2020 | - | - | - | - |
| Music Emotion Recognition with Graph Convolutional Networks | 2023 | - | Graph Convolutional Networks | - | - |
| Music Emotion Recognition Using Transformers with Rhythm Attention | 2023 | - | Transformers with Rhythm Attention | - | - |
| Music Recommendation with Emotion-Aware Generative Adversarial Networks | 2022 | - | Emotion-Aware Generative Adversarial Networks | - | - |
| Generating Emotional Music with Conditional Variational Autoencoders | 2021 | - | Conditional Variational Autoencoders | - | - |
| The DEAP Dataset for Recognition of Human Emotions | 2012 | - | - | - | DEAP Dataset |
| A Dataset for Music Emotion Recognition in the Wild | 2018 | - | - | - | Music Emotion Recognition in the Wild Dataset |
| Music Emotion Recognition from Lyrics Using Deep Attention Networks | 2020 | Lyrics | Deep Attention Networks | - | - |
| Music Emotion Recognition with Multimodal Fusion of Lyrics and Spectrograms | 2022 | Audio, Lyrics, Spectrograms | Multimodal Fusion | - | - |

