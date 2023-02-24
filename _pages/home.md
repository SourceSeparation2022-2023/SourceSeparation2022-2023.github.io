---
title: ""
layout: single
permalink: /
author_profile: true
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
#   overlay_image: /images/particles.jpg
excerpt: "Abstract"
---

## Introduction
<html>
<div style="text-align: justify">
<p>
This project is part of the <a href="https://www.atiam.ircam.fr/en/" target="_blank" rel="noopener noreferrer">ATIAM</a> master. The aim of this project is to separate instruments from a quintet as if each instrument was recorded alone, but they indeed have been recorded playing together. This technique is called source separation. A effort was made to link signal processing with acoustics and sound recording in order to make better informed choices, mainly when choosing and placing the microphones.
</p>
<p>
You can read our report <a href="/images/PAM_SourceSeparation.pdf" target="_blank" rel="noopener noreferrer">SoundSeparation.pdf</a>
</p>
</div>
</html>
## Abstract

<html>
<div style="text-align: justify">
<p>
Music Source Separation (MSS) is the process of separating individual audio signals from a mixed recording containing multiple sound sources, such as different musical instruments, vocals and ambient noise. Its various applications include remixing, transcription and music recommendation. In the context of real acoustic recordings, the separation task is particularly challenging due to the complexity and variability of acoustic instruments and recording conditions such as room acoustics and microphone directivity. We propose the use of Non-negative Matrix Factorization (NMF) algorithms for this task, and in our multi-channel setting, we aim to implement efficient, conditioned versions of this algorithm to be applied to musical recordings performed in a known and controlled context. We investigate methods of informing this algorithm by conditioning on temporal and spectral information from the instruments, that were specifically registered at the time of the recording for this purpose. To this end, we conducted a professional-level recording of a chamber music quintet.
</p>
<p>
We have compared our results with other state-of-the-art algorithms, obtaining comparable results on benchmark datasets, and we have carried out subjective evaluation according to the MUSHRA protocol, where we see a good performance of our algorithm. We observe a strong effect of the processing of the recording, which helps or hinders the separation depending on the instrument. Our approach confirms the versatility of the FastMNMF algorithm and the possibility of extending and making these algorithms more versatile.
</p>

</div>
</html>

*Keywords: Music, Source separation, Non-Negative Matrix Factorization, Live Recording, Acoustics*

## Authors

[Pierre Chouteau](mailto:pierre.chouteau@atiam.fr), [Henri Desvallées](mailto:henri.desvallees@atiam.fr), [Louis Lalay](mailto:louis.lalay@atiam.fr), [Mathilde Lefebvre](mailto:mathilde.lefebvre@atiam.fr), [Ivan Meresman-Higgs](mailto:meresmanhiggs@atiam.fr), [Théo Nguyen](mailto:theo.nguyen@atiam.fr)