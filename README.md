# <p align=center> List of datasets and models for music emotion prediction

This repo supplements our survey: Are We There Yet? A Brief Survey of Music Emotion Prediction Datasets, Models and Outstanding Challenges

- Paper: [arXiv](https://arxiv.org/abs/2406.08809)
- Authors: [Jaeyong Kang](https://scholar.google.com/citations?user=kEI6KkIAAAAJ&hl=en), [Dorien Herremans](https://scholar.google.com/citations?user=Hp5W5f0AAAAJ&hl=en)
</p>

> **<p align="justify"> Abstract:** *Deep learning models for music have advanced drastically in recent years, but how good are machine learning models at capturing emotion, and what challenges are researchers facing? In this paper, we provide a comprehensive overview of the available music-emotion datasets and discuss evaluation standards as well as competitions in the field. We also offer a brief overview of various types of music emotion prediction models that have been built over the years, providing insights into the diverse approaches within the field. Through this examination, we highlight the challenges that persist in accurately capturing emotion in music, including issues related to dataset quality, annotation consistency, and model generalization. Additionally, we explore the impact of different modalities, such as audio, MIDI, and physiological signals, on the effectiveness of emotion prediction models. Recognizing the dynamic nature of this field, we have complemented our findings with an accompanying GitHub repository. This repository contains a comprehensive list of music emotion datasets and recent predictive models.* </p>

A curated list of Datasets and Models for Music Emotion Recognition (MER)

## Overview
- [List of music-emotion datasets](#list-of-music-emotion-datasets)
- [List of music emotion prediction models](#List-of-music-emotion-prediction-models)

## Citation
If you find these lists useful, please [cite our orginal paper](https://arxiv.org/abs/2406.08809). 

```
@conference {2024,
	title = {Are we there yet? A brief survey of Music Emotion Prediction Datasets, Models and Outstanding Challenges},
	booktitle = {arXiv:2406.08809},
	year = {2024},
	url = {https://arxiv.org/abs/2406.08809},
	author = {J. Kang and D. Herremans}
}
```

## Contribute
Want to contribute your models or datasets? Simply do a pull request. 

## List of music-emotion datasets

| Dataset                             | Year | # of instances | Length  | Type          | Categorical | Dimensional | Dynamic | Induced  |
|-------------------------------------|------|----------------|---------|---------------|-------------|-------------|---------|----------|
| MoodsMIREX                          | 2007 | 269            | 30s     | MP3           | 5 labels    | -           | Static  | Perceived|
| CAL500                              | 2007 | 500            | full    | MP3           | 174 labels  | -           | Static  | Perceived|
| Yang-Dim                            | 2008 | 195            | 25s     | WAV           | -           | Russell     | Static  | Perceived|
| MoodSwings                          | 2008 | 240            | 15s     | MP3           | -           | Russell     | Dynamic | Perceived|
| NTWICM                              | 2010 | 2,648          | full    | MP3           | -           | Russell     | Static  | Perceived|
| Soundtrack                          | 2011 | 470            | 15s-1m  | MP3           | 6 labels    | 3 dimensions| Static  | Perceived|
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
| DEAM                                | 2018 | 2,058          | 45s     | MP3           | -           | Russell     | Both    | Perceived|
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


## List of music emotion prediction models

| Ref.                                                                                   | Year | Modalities     | Approach                                     | Emotion Model | Dataset                        |
|----------------------------------------------------------------------------------------|------|----------------|----------------------------------------------|---------------|--------------------------------|
| A new model for emotion prediction in music                                            | 2020 | Audio, Lyrics  | Machine learning (e.g., SVM, NB)             | Russell       | PMEmo                          |
| Multi-view neural networks for raw audio-based music emotion recognition               | 2020 | Audio          | CNN, LSTM                                    | Russell       | Solymani et al.’s dataset       |
| Musical instrument emotion recognition using deep recurrent neural network             | 2020 | Audio          | LSTM                                         | 4 classes     | Self-built                     |
| A multimodal music emotion classification method based on multifeature combined network classifier | 2020 | Audio          | CNN-LSTM                                     | 4 classes     | Last.fm                        |
| Attentive RNNs for Continuous-time Emotion Prediction in Music Clips                   | 2020 | Audio          | Attentive LSTM                               | Russell       | Solymani et al.’s dataset       |
| The multiple voices of musical emotions: source separation for improving music emotion recognition models and their interpretability | 2020 | Audio          | Source separation, CNN                       | Russell       | PMEmo                          |
| Cochleogram-based approach for detecting perceived emotions in music                   | 2020 | Audio          | Cochleogram, CNN                             | Russell       | Solymani et al.’s dataset       |
| Recognition of emotion in music based on deep convolutional neural network             | 2020 | Audio          | CNN, Local Attention                         | Quadrants     | Soundtrack, Bi-Modal            |
| Emotion and theme recognition in music using attention-based methods                   | 2020 | Audio          | Attention Based Neural Networks              | 56 classes    | MTG-Jamendo                        |
| Regression-based Music Emotion Prediction using Triplet Neural Networks                | 2020 | Audio          | Triplet Neural Networks                      | Russell       | DEAM                           |
| Research on music emotion classification based on CNN-LSTM network                    | 2021 | Audio          | CNN-LSTM                                     | Russell       | DEAM                           |
| Music emotion recognition using convolutional long short term memory deep neural networks | 2021 | Audio        | CNN, LSTM+DNN                                | 3 classes     | Self-built                     |
| Recognizing Song Mood and Theme: Clustering-based Ensembles                            | 2021 | Audio          | Clustering-based Ensembles                   | 56 classes    | MTG-Jamendo                        |
| Semi-supervised music emotion recognition using noisy student training and harmonic pitch class profiles | 2021 | Audio          | Semi-Supervised, Noisy Student Training      | 56 classes    | MTG-Jamendo                        |
| Frequency Dependent Convolutions for Music Tagging                                     | 2021 | Audio          | Frequency Dependent Convolutions             | 56 classes    | MTG-Jamendo                        |
| SELAB-HCMUS at MediaEval 2021: Music Theme and Emotion Classification with Co-teaching Training Strategy | 2021 | Audio        | CNN, Co-teaching Training Strategy           | 56 classes    | MTG-Jamendo                        |
| Music emotion recognition using recurrent neural networks and pretrained models        | 2021 | Audio          | LSTM, Pretrained Models                      | Russell       | Self-built                     |
| Transformer-based approach towards music emotion recognition from lyrics               | 2021 | Lyrics         | Transformers                                 | Russell       | MoodyLyrics, MER               |
| Tracing back music emotion predictions to sound sources and intuitive perceptual qualities | 2021 | Audio       | Source-separation based explainer            | Russell       | DEAM, Midlevel, PMEmo           |
| A generative adversarial network model based on intelligent data analytics for music emotion recognition under IoT | 2021 | Audio | Generative Adversarial Network               | 2 classes     | Self-built                     |
| Deep learning-based late fusion of multimodal information for emotion classification of music video | 2021 | Audio, Video  | CNN                                          | 6 classes     | Self-built                     |
| A multi-genre model for music emotion recognition using linear regressors              | 2021 | Audio          | Linear Regressors                            | Russell       | Self-built                     |
| Study on music emotion recognition based on the machine learning model clustering algorithm | 2022 | Audio        | Clustering, Machine Learning (e.g., SVM)     | Russell       | Solymani et al.'s dataset       |
| A novel multi-task learning method for symbolic music emotion recognition              | 2022 | MIDI           | Multi-Task Learning                          | Quadrants     | EMOPIA, VGMIDI                 |
| Feature selection approaches for optimising music emotion recognition methods          | 2022 | Audio          | Feature Selection, SVR, RF                   | Russell       | DEAM                 |
| Predicting emotion from music videos: exploring the relative contribution of visual and auditory information to affective responses | 2022 | Audio, Video  | LSTM                                          | Russell       | Self-built                     |
| MERGE Lyrics: Music Emotion Recognition next Generation--Lyrics Classification with Deep Learning | 2022 | Lyrics      | Deep Learning, BERT                          | Quadrants     | MIR Lyrics Emotion             |
| Music emotion recognition based on segment-level two-stage learning                    | 2022 | Audio          | CNN, LSTM                                    | Russell       | PMEmo                          |
| Emotional classification of music using neural networks with the MediaEval dataset     | 2022 | Audio          | SVM, Random Forest, MLP                      | Russell       | DEAM                 |
| Multi-Modality in Music: Predicting Emotion in Music from High-Level Audio Features and Lyrics | 2023 | Audio, Lyrics | Multi-Modality                               | Russell       | DMDD                           |
| Music emotion recognition based on a neural network with an inception-gru residual structure | 2023 | Audio       | Inception-GRU Residual                       | Quadrants     | Soundtrack                     |
| Modeling emotion dynamics in song lyrics with state space models                       | 2023 | Lyrics         | State Space Models                           | 6 classes     | LyricsEmotions                 |
| Tollywood Emotions: Annotation of Valence-Arousal in Telugu Song Lyrics                | 2023 | Lyrics         | Fine-tuned XLMRoBERTa                        | Russell       | Self-built                     |
| Multimodal music emotion recognition in Indonesian songs based on CNN-LSTM, XLNet transformers | 2023 | Audio, Lyrics | CNN-LSTM, XLNet Transformers                 | 3 classes     | Self-built                     |
| Modularized composite attention network for continuous music emotion recognition       | 2023 | Audio          | Attention Mechanism                          | Russell       | DEAM, PMEmo                    |
| Automatic music emotion classification model for movie soundtrack subtitling based on neuroscientific premises | 2023 | Audio       | CNN                                          | 4 classes     | Musical Excerpts               |
| Transformer-based automatic music mood classification using multi-modal framework      | 2023 | Audio, Lyrics  | Transformers                                 | Quadrants     | MoodyLyrics                    |
| Music Emotion Prediction Using Recurrent Neural Networks                               | 2024 | Audio          | RNN, BRNN, LSTM                              | Quadrants     | 4Q audio, MTG-Jamendo          |
| MMD-MII model: a multilayered analysis and multimodal integration interaction approach revolutionizing music emotion classification | 2024 | Audio, Lyrics | VGGish, ALBERT                               | 4 classes     | DEAM, FMA                      |
| Verse1-Chorus-Verse2 Structure: A Stacked Ensemble Approach for Enhanced Music Emotion Recognition | 2024 | Audio, Lyrics | Stacked Ensemble Models                      | 4 classes     | Self-built                     |
| A GAI-based multi-scale convolution and attention mechanism model for music emotion recognition and recommendation from physiological data | 2024 | Audio      | Multi-scale Parallel Convolution             | 8 classes     | PMEmo, Soundtrack, RAVDESS     |
| Improved differential evolution algorithm based convolutional neural network for emotional analysis of music data | 2024 | Audio         | CNN with Differential Evolution              | 4 classes     | self-built, DEAM               |
