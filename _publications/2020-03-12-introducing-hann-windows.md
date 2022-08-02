---
title: "Introducing Hann windows for reducing edge-effects in patch-based image segmentation"
collection: publications
permalink: /publication/2020-03-12-introducing-hann-windows.md
excerpt: 'This article shows how to combine overlapping patches when performing large image segmentation with deep learning models.'
date: 2020-03-12
venue: 'PloS one'
paperurl: 'https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0229839'
citation: 'Pielawski, Nicolas, and Carolina Wählby. "Introducing Hann windows for reducing edge-effects in patch-based image segmentation." <i>PloS one</i> 15.3 (2020): e0229839.'
---
Sometimes the GPU memory is not big enough to contain both a Convolutional Neural
Networks and large images at the same time. This article shows a way to cut images into
overlapping patches that fit the GPU memory and removes edge artefacts that appear when
the patches are not-overlapping.

[Download paper here](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0229839)
[ArXiV version here](https://arxiv.org/abs/1910.07831)
[Python example](https://gist.github.com/npielawski/7e77d23209a5c415f55b95d4aba914f6)

Recommended citation: Pielawski, Nicolas, and Carolina Wählby. "Introducing Hann windows for reducing edge-effects in patch-based image segmentation." <i>PloS one</i> 15.3 (2020): e0229839.
