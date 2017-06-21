# BSc Thesis: Voice Conversion using Deep Learning

BSc thesis on applying Deep Learning to convert the speaker features on voice signals, presented in [Telecom BCN](http://etsetb.upc.edu/en), Barcelona on May 2017

## Abstract

In this project we present a first attempt at a Voice Conversion system based on Deep Learning in which the alignment between the training data is intrinsic to the model. Our system is structured in three main blocks. The first performs a vocoding of the speech (we have used Ahocoder for this task) and a normalization of the data. The second and main block consists of a Sequence-to-Sequence model. It consists of an RNN-based encoder-decoder structure with an Attention Mechanism. Its main strengts are the ability to process variable-length sequences, as well as aligning them internallly. The third block of the system performs a denormalization and reconstructs the speech signal. For the development of our system we have used the Voice Conversion Challenge 2016 dataset, as well as a part of the TC-STAR dataset. Unfortunately we have not obtained the results we expected. At the end of this thesis we present them and discuss some hypothesis to explain the reasons behind them.

## Contents

* Introduction
* State of the art in Voice Conversion
* Methodology
  * Datasets
  * Preparation of the datasets
  * Proposed Models
    * Baseline
    * Sequence-to-Sequence
* Results

### Reference

Please cite this work if it is useful for your research:

```
@mastersthesis{aparicio2017voice,
  author       = {Aparicio Isarn, Albert}, 
  title        = {Voice Conversion using Deep Learning},
  school       = {Universitat Polit{\`e}cnica de Catalunya},
  year         = 2017,
  month        = 5
}
```

### Author:

Albert Aparicio ([e-mail](albert.aparicio.isarn@gmail.com))
