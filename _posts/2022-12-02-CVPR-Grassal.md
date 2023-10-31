---
layout: post
title: "Neural Head Avatars from Monocular RGB Videos"
categories: publications
authors: Philip-William Grassal1    Malte Prinzler1    Titus Leistner    Carsten Rother    Matthias Nießner    Justus Thies
venue: "CVPR 2022"
arxiv: https://arxiv.org/abs/2112.01554
code: https://github.com/philgras/neural-head-avatars
image: /images/Rother_CVPR.png
---

We present Neural Head Avatars, a novel neural representation that explicitly models the surface geometry and
appearance of an animatable human avatar that can be used for teleconferencing in AR/VR or other applications in
the movie or games industry that rely on a digital human. Our representation can be learned from a monocular RGB
portrait video that features a range of different expressions and views. Specifically, we propose a hybrid 
representation consisting of a morphable model for the coarse shape and expressions of the face, and two feed-forward networks,
predicting vertex offsets of the underlying mesh as well as a view- and expression-dependent texture. We demonstrate
that this representation is able to accurately extrapolate to unseen poses and view points, and generates natural 
expressions while providing sharp texture details. Compared to previous works on head avatars, our method provides a
disentangled shape and appearance model of the complete human head (including hair) that is compatible with the
standard graphics pipeline. Moreover, it quantitatively and qualitatively outperforms current state of the art in terms of
reconstruction quality and novel-view synthesis.