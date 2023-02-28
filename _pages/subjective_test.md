---
title: "Subjective test"
layout: single
permalink: /mushra
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
#   overlay_image: /images/particles.jpg
excerpt: "Explanations of the Mushra test"
---

# The MUSHRA test
For evaluating our algorithmon real audio, we lack the ground truth wich is the isolated instrument. Therefore we need another mean of evaluation, and we built a subjective test. The test is available for now [here](https://sourceseparation2022-2023.github.io/webmushra/).

<!-- Here include some description of Mushra and Webmushra -->

Subjective evaluation procedures involve human evaluators assigning scores to the output of the source separation system. The state-of-the-art for subjective evaluation is called Multiple Stimuli with Hidden Reference and Anchor (MUSHRA), the test should be developed following the International Telecommunications Union’s recommendations ITU. It is ideally performed by well-trained audio engineers in a sound-treated room and compares the qualities of various conditioned sound files with a reference. Among the files to compare should be a hidden reference and at least one hidden anchor, an intentionally bad variant of the audio which is traditionally obtained by low-pass filtering. These are meant to provide boundaries across evaluators, and raise a flag if any rating may have been incorrectly performed.
