# List of datasets and models for music emotion prediction

This repo supplements our survey: Are We There Yet? A Brief Survey of Music Emotion Prediction Datasets, Models and Outstanding Challenges

- Paper: [arXiv](https://arxiv.org/abs/2406.08809)
- Authors: [Jaeyong Kang](https://scholar.google.com/citations?user=kEI6KkIAAAAJ&hl=en), [Dorien Herremans](https://scholar.google.com/citations?user=Hp5W5f0AAAAJ&hl=en)


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
| Last.fm subset of MSD               | 2011 | 505,216        | full    | Metadata only |listener tags| -           | Static  | Perceived|
| DEAP                                | 2012 | 120            | 60s     | YouTube id    | -           | Russell     | Static  | Induced  |
| Panda et al.'s dataset              | 2013 | 903            | 30s     | MP3, MIDI     | 21 labels   | -           | Static  | Perceived|
| Solymani et al.'s dataset           | 2013 | 1000           | 45s     | MP3           | -           | Russell     | Both    | Perceived|
| CAL500exp                           | 2014 | 3,223          | 3s-16s  | MP3           | 67 labels   | -           | Static  | Perceived|
| AMG1608                             | 2015 | 1,608          | 30s     | WAV           | -           | Russell     | Static  | Perceived|
| Emotify                             | 2016 | 400            | 60s     | MP3           | GEMS        | -           | Static  | Induced  |
| Moodo                               | 2016 | 200            | 15s     | WAV           | -           | Russell     | Static  | Perceived|
| Malheiro et al.'s dataset           | 2016 | 200            | 30s     | Audio, Lyrics | Quadrants   | -           | Static  | Perceived|
| CH818                               | 2017 | 818            | 30s     | MP3           | -           | Russell     | Static  | Perceived|
| MoodyLyrics                         | 2017 | 2,595          | full    | Lyrics        | 4 labels    | -           | Static  | Perceived|
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
| Popular Hooks                       | 2024 | 38,694         | hooks   | Video, Audio, Lyrics | Quadrants   | -           | Static  | Perceived|
| Affolter and Rohrmeier's dataset    | 2024 | 5,892          | full    | Spotify id    | 8 labels    | -           | Static  | Perceived|
| XMIDI                               | 2025 | 108,023        | full    | MIDI          | 11 labels   | -           | Static  | Perceived|

### Additional information
#### Moods MIREX
* Author: Hu, X., Downie, J.S., Laurier, C., Bay, M., Ehmann, A.F.
* Description and music styles: Selection of the libraries of Associated Production Music (APM), “the world’s leading production music library… offering every imaginable music genre from beautiful classical music recordings to vintage rock to current indie band sounds".
* Annotation strategy: The pieces were rated by 3 raters, and only a subset of agreement by 2 out of 3 is extracted. 
* Annotation (categorical): Cluster 1 (passionate, rousing, confident, boisterous, rowdy), Cluster 2 (rollicking, cheerful, fun, sweet, amiable/good natured), Cluster 3 (literate, poignant, wistful, bittersweet, autumnal, brooding), Cluster 4 (humorous, silly, campy, quirky, whimsical, witty, wry), Cluster 5 (aggressive, fiery, tense/anxious, intense, volatile, visceral)
* Link: Offline

#### CAL500
* Author: Turnbull, D., Barrington, L., Torres, D., Lanckriet G. 
* Description and music styles: Songs were picked from the authors' personal collection of western popular 
music recorded within the last 50 years.
* Annotation strategy: The authors paid 66 undergraduate students to annotate the CAL500 corpus with semantic 
concepts from the vocabulary.  Participants were rewarded $10 for a one hour annotation block spent listening to the music.
* Annotation (categorical): 18 emotions, found by Skowronek et al. (2006) to be both important and easy to identify, were rated on a scale from one to three (e.g., not happy, neutral, happy).
* Link: http://calab1.ucsd.edu/~datasets/cal500/

#### Yang-Dim
* Author: Yang, Y.-H., Lin, Y.-C, Su, Y.-F, Chen, H.-H. 
* Description and music styles: The dataset contains 195 popular songs from Western, Chinese, and Japanese albums. 
* Annotation strategy: Subjects (most college students) are asked to listen to a subset of music dataset and to choose two values, each ranges from -1.0 to 1.0 in 11 levels, to indicate their feeling about the AV values of the music sample. The ground truth is set as the mean of the AV values of all subjects tested. On the average, more than ten pairs of AV values are collected from the subjective test for each music sample.
* Annotation (dimensional): Arousal and valence
* Link: http://mac.citi.sinica.edu.tw/~yang/MER/taslp08/#Data

#### MoodSwings
* Author: Kim, Y., Schmidt, E., Emelle, L.
* Description and music styles: The authors used US pop music to collect time-varying perception of emotions.
* Annotation strategy: Two players from a game used the mouse to annotate the segment over a continuous AV space.
* Annotation (dimensional): Time-continuous arousal and valence annotation (1 Hz)
* Link: Offline

#### Now That's What I Call Music (NTWICM)
* Author: Schuller, B., Dorfner, J., Gerhard, R.
* Description and music styles: For building up a ground truth music database the compilation “Now That’s What I Call Music!” (U. K. series, volumes 1–69, double CDs, each) is selected. It represents very well most music styles which are popular today; that ranges from Pop and Rock music over Rap, R&B to electronic dance music as Techno or House.
* Annotation strategy: 4 raters gave static annotations for complete songs for arousal and valence in a discrete range of [−2,−1, 0, 1, 2]. 
* Annotation (dimensional): Arousal and valence [−2,−1, 0, 1, 2].
* Link: http://openaudio.eu/NTWICM-Mood-Annotation.arff (annotations) 

#### Soundtracks
* Author: Eerola, T. & Vuoskoski, J. K.
* Description and music styles: This dataset we refer to as "Film soundtracks" are designed to overcome at least some of the problems mentioned above since they contain not that well known examples (although some could be identified by film aficionados).
* Annotation strategy: The selection of the excerpts has been done in terms of dimensional and discrete emotion model and evaluated by a pilot study. The initial ratings were made by 12 expert musicologists for both dimensional and discrete models. These ratings were then re-tested with 116 university students.
* Annotation: categorical and dimensional
* Link: https://osf.io/p6vkg/

#### MoodSwings Turk
* Author: Speck, J.A., Schmidt, E.M., Morton, B.G. and Kim, Y.E.
* Description and music styles: The authors used US pop music to collect time-varying perception of emotions.
* Annotation strategy: Crowdsourced MTurk.
* Annotation (dimensional): Time-continuous arousal and valence annotation (1 Hz)
* Link: Offline

#### Last.fm subset of MSD
* Author: Bertin-Mahieux, T., Ellis, D.P.W., Whitman, B., & Lamere, P.
* Description and music styles: A large-scale dataset derived from user-generated tags and similarity data on Last.fm, linked to the Million Song Dataset. Covers a broad range of Western popular music genres including pop, rock, electronic, and hip-hop.
* Annotation strategy:  Tags and song similarities were obtained from the Last.fm API. Tags reflect listener-generated annotations, collected via Last.fm’s crowd-based platform. Song similarities were computed by Last.fm based on user listening behavior.
* Annotation: Categorical, based on listener-provided tags. No predefined emotion taxonomy; tag frequency and co-occurrence patterns can be leveraged for emotion-related studies.
* Link: http://millionsongdataset.com/lastfm/

#### DEAP
* Author: Koelstra, S., Muehl, C., Soleymani, M., Lee, J.-S., Yazdani, A., Ebrahimi, T., Pun, T., Nijholt, A., Patras, I.
* Description and music styles: From the 120 original videos from YouTube, 60 were manually selected, while the remaining 60 were selected via Last.FM affective tags. EEG and physiological signals were recorded and each participant also rated the videos as above. For 22 participants frontal face video was also recorded.
* Annotation strategy: The participants ratings, physiological recordings and face video of an experiment where 32 volunteers (mostly European students) watched a subset of 40 of the above music videos. EEG and physiological signals were recorded and each participant also rated the videos as above. For 22 participants frontal face video was also recorded.
* Annotation: Dimensional (arousal, valence, and dominance)
* Link: http://www.eecs.qmul.ac.uk/mmv/datasets/deap/

#### Panda et al.'s dataset
* Author: Panda, R., Malheiro, R., Rocha, B., Oliveira, A., and Paiva, R. P.
* Description and music styles: A multi-modal dataset created from the AllMusic database, comprising 903 Western music excerpts across various genres. Each excerpt is paired with corresponding MIDI files and lyrics, enabling analysis from audio, symbolic, and textual perspectives.
* Annotation strategy: Emotion labels were derived from listener-assigned emotion tags on AllMusic, mapped to the 5 emotion clusters defined in the MIREX Mood Classification Task.
* Annotation: Categorical — 21 tags grouped into 5 MIREX-defined emotion clusters.
* Link: http://mir.dei.uc.pt/resources/MIREX-like_mood.zip

#### Solymani et al.'s dataset
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

#### CAL500exp
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### AMG1608
* Author: Chen, Y.-A, Yang, Y.-H., Wang, J.-C., Chen, H.-H.
* Description and music styles: The dataset contemporary Western music from AMG, which has 34 distinct mood categories defined by music editors.
* Annotation strategy: Each subject is asked to annotate 13 songs and the subject can annotate a song by placing the cursor on the panel to indicate the location of the perceived VA value of the song.
* Annotation (dimensional): Arousal and valence real values between [-1,1] for whole excerpt.
* Link: https://amg1608.blogspot.com/

#### Emotify
* Author: Aljanaki, A., Wiering, F., Veltkamp, R.C.
* Description and music styles: The selected songs include mainly four genres (rock, classical, pop and electronic) music. 
* Annotation strategy: The annotations were collected using GEMS scale (Geneva Emotional Music Scales). The annotations produced by the game are spread unevenly among the songs, which is caused both by design of the experiment and design of the game. Participants could skip songs and switch between genres, and they were encouraged to do so, because induced emotional response does not automatically occur on every music listening occasion. 
* Annotation (categorical): Nine categories (amazement, solemnity, tenderness, nostalgia, calmness, power, joyful activation, tension, sadness)
* Link: http://www2.projects.science.uu.nl/memotion/emotifydata/

#### Moodo
* Authors: M Pesek, G Strle, A Kavčič, M Marolt 
* Description and music styles: The dataset contains 200 excerpts (15 seconds). 20 from electronic acoustic, 20 from ethno, 80 from popular (Jamendo) and 80 from movies (Eerola and Vuoskoski, 2010).  
* Annotation strategy: 741 participants where presented with 10 music excerpts and instructed to choose a color best associated with the music excerpt.
* Annotation (dimensional): Arousal and valence real values between [-1,1] this was mapped to a color.
* Link: [http://moodo.musiclab.si](http://moodo.musiclab.si)

#### Malheiro et al.'s dataset
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### CH818
* Author: Hu, X., Yang, Y.
* Description and music styles: Chinese Pop songs released in Taiwan, Hong Kong and Mainland China.
* Annotation strategy: Each clip was annotated by three music experts who were born and raised in Mainland China and thus were with a Chinese cultural background. The annotation was done with an interface consisting of two sliding bars of continuous real values between [-10,10]. 
* Annotation (dimensional): Arousal and valence real values between [-10,10] for whole excerpt.
* Link: Offline

#### MoodyLyrics
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### 4Q Emotion Dataset
* Author: Panda R., Malheiro R., Paiva R. P.
* Description and music styles: The AllMusic API served as the source of musical information, providing metadata such as artist, title, genre and emotion information, as well as 30-second audio clips for most songs. Mostly popularly consumed music.
* Annotation strategy: Collected from AllMusic API, emotion tags are selected from the original AllMusic Tags by intersecting them with the Warriner’s list. Finally, a manual blind validation is conducted by subjects.
* Annotation (categorical): Q1 (A+V+), Q2 (A+V-), Q3(A-V-), Q4 (A-V+)
* Link: http://mir.dei.uc.pt/downloads.html 

#### MediaEval Database for Emotional Analysis in Music (DEAM)
* Author: Soleymani, M., Aljanaki, A., Yang, Y.
* Description and music styles: Royalty-free music from several sources: freemusicarchive.org (FMA), jamendo.com,
and the medleyDB datase. The excerpts which were annotated are available in the same package song ids between 1 and 2058. The dataset consists of 2014 development set (744 songs), 2014 evaluation set (1000 songs) and 2015 evaluation set (58 songs). Includes rock, pop, soul, blues, electronic, classical, hip-hop, international, experimental, folk, jazz, country and pop genres.
* Annotation strategy: Crowdsourced MTurk with each excerpt annotated at least by 10 workers. Both arousal and valence were annotated separately. Additional static annotations were collected for the whole 45 second exceprts after dynamic annotations. 
* Annotation (dimensional): Time-continuous arousal and valence annotation (1 Hz)
* Link: http://cvml.unige.ch/databases/DEAM/

#### PMEmo
* Author: Zhang, K., Zhang, H., Li, S., Yang, C., Sun, L.
* Description and music styles: The authors gathered songs popular all around the world: the Billboard Hot 100, the iTunes Top 100 Songs (USA), and the UK Top 40 Singles Chart. They obtained songs available from these charts from 2016 to 2017.
* Annotation strategy: Similar to DEAM, the annotation was done with the slider to collect dynamic annotations at a sampling rate of 2 Hz. Additionally, annotators should make a static annotation for the whole music excerpt on nine-point scale after finishing dynamic labelling. A total of 457 subjects (236 females and 221 males) are recruited to participate in this work. The electrodermal activity was sampled continuously at a sampling rate of 50 Hz.
* Annotation (dimensional): Time-continuous arousal and valence annotation (2 Hz)
* Link: https://github.com/HuiZhangDB/PMEmo

#### RAVDESS
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

#### DMDD
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### Jamendo Mood and Theme Subset (MTG-Jamendo)
* Author: Bogdanov, D., Porter A., Tovstogan P., & Won M. 
* Description and music styles: The MTG-Jamendo Dataset is an open dataset for music auto-tagging and a subset of the dataset is used in the Emotion and Theme Recognition in Music Task within MediaEval 2019. The dataset contains 87 genre tags, so there is style diversity. 
* Annotation strategy: The 56 mood/theme tags were crowdsourced from social media tags on the Jamendo platform. Hence, the annotations can be single- or multi-labeled depending on the excerpt. 
* Annotation (categorical): 56 mood/theme tags
* Link: https://multimediaeval.github.io/2019-Emotion-and-Theme-Recognition-in-Music-Task/

#### VGMIDI
* Author: Ferreira, L., Whitehead, J.
* Description and music styles: VGMIDI is a dataset of 200 MIDI labelled piano pieces (video game soundtracks).
* Annotation strategy: Each piece was annotated by 30 human subjects according to a valence-arousal model of emotion. The authors ask the annotators to write two to three sentences describing the short pieces they listened to.
* Annotation (dimensional): Time-continuous arousal and valence annotation
* Link: https://github.com/lucasnfe/vgmidi

#### Turkish Music Emotion
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### EMOPIA
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### MER500
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### Music4all
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### CCMED-WCMED
* Author: Fan, J., Yang, Y.-H., Gong, K, Pasquier, P.
* Description and music styles: The dataset contains 400 excerpts collected from Western classical music recordings and 400 excerpts collected from Chinese classical music recordings.
* Annotation strategy: Two crowdsourcing experiments were carried out to collect emotional annotations (arousal and valence). The authors used a ranking-based method. Instead of providing absolute ratings, participants do pairwise comparisons by deciding which audio excerpt has higher arousal/valence.
* Annotation (dimensional): Arousal and valence real values between [-1,1] for whole excerpt.
* Link: https://metacreation.net/ccmed_wcmed_soundscape/

#### MuSe
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

#### HKU956
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### MERP
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### MuVi
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### YM2413-MDB	
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link: 

#### MusAV
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

#### EmoMV
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

#### Indonesian Song
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

#### TROMPA-MER
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

#### Music-Mouv
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

#### ENSA
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

#### EMMA
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

#### SiTunes	
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

#### MERGE	
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

### Popular Hooks	
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

### Affolter and Rohrmeier's dataset	
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:

### XMIDI
* Author: 
* Description and music styles: 
* Annotation strategy: 
* Annotation: 
* Link:


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
