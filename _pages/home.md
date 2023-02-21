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

This project is part of the [ATIAM](https://www.atiam.ircam.fr/en/) master. 

## Abstract

Music Source Separation (MSS) is the process of separating individual audio signals from a mixed recording containing multiple sound sources, such as different musical instruments, vocals and ambient noise, and its various applications include remixing, transcription and music recommendation. 
In the context of real acoustic recordings, the separation task is particularly challenging due to the complexity and variability of acoustic instruments and recording conditions such as room acoustics and microphone directivity.%,  add some challenges for a non-degraded MSS. 
We propose the use of Non-Negative Matrix Factorization (NMF) separation algorithms, where an easily interpretable time-frequency representation of the power spectrogram aims to decompose each instrument recording into a dictionary of notes (frequency basis) and a time activation basis (time basis), reminiscent of a musical score. 
In our multi-channel setting, we aim to implement efficient, conditioned versions of this algorithm to be applied to musical recordings performed in a known and controlled context, to investigate methods of informing this algorithm for improved performance.
To this end, we conducted a professional-level recording of a chamber music quintet.
We implemented a set of standard NMF algorithms that can be conditioned on temporal and spectral information from the instruments that were specifically registered at the time of the recording for this purpose.
    
We have compared our results with other SOTA algorithms,
{\color{red}here say something about the objective results},
and performed subjective evaluation according to the MUSHRA protocol, {\color{red}here say something about the subjective results}. 
Our approach confirms the versatility of the FastMNMF algorithm and the possibility of extending and making these algorithms more versatile. %Our work provides  
    

*Keywords*: Music, Source separation, Non-Negative Matrix Factorization, Live Recording, Acoustics

## Authors

[Pierre Chouteau](mailto:pierre.chouteau@atiam.fr), [Henri Desvallées](mailto:henri.desvallees@atiam.fr), [Louis Lalay](mailto:louis.lalay@atiam.fr), [Mathilde Lefebvre](mailto:mathilde.lefebvre@atiam.fr), [Ivan Meresman-Higgs](mailto:meresmanhiggs@atiam.fr), [Théo Nguyen](mailto:theo.nguyen@atiam.fr)