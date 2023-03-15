---
title: "A Synthetic Corpus Generation Method for Neural Vocoder Training"
collection: publications
permalink: /publication/2022-Synthcoder
excerpt: ''
date: 2023-01-02
venue: 'ICASSP'
paperurl: ''
citation: 'Zilin Wang, Peng Liu, <b>Jun Chen</b>, Zhiyong Wu, Chao Weng, Dan Su, Helen Meng. &quot;Synthetic Data is All You Need? Towards Universal Neural Vocoding&quot;. <i>IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)</i>, 2023.'

---
Abstract
===
Nowadays, neural vocoders are preferred for their ability to synthesize high-fidelity audio. However, training a neural vocoder requires a massive corpus of high-quality real audio, and the audio recording process is often labor-intensive. In this work, we propose a synthetic corpus generation method for neural vocoder training, which can easily generate synthetic audio with an unlimited number at nearly no cost. We explicitly model the prior characteristics of audio from multiple target domains simultaneously (e.g., speeches, singing voices, and instrumental pieces) to equip the generated audio data with these characteristics. And we show that our synthetic corpus allows the neural vocoder to achieve competitive results without any real audio in the training process. To validate the effectiveness of our proposed method, we performed empirical experiments on both speech and music utterances in subjective and objective metrics. The experimental results show that the neural vocoder trained with the synthetic corpus produced by our method can generalize to multiple target scenarios and has excellent singing voice (MOS: 4.20) and instrumental piece (MOS: 4.00) synthesis results.