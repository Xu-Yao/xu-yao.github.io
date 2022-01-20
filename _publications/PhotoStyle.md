---
title: "Photo style transfer with consistency losses"
collection: publications
permalink: /publications/PhotoStyle
venue: "ICIP"
date: 2019-09-22
citation: 'Xu Yao, Gilles Puy, and Patrick Pérez <br /> <i>ICIP 2019</i>'
---
[[PDF]](https://arxiv.org/pdf/2005.04408.pdf)

## Abstract
We address the problem of style transfer between two photos and propose a new way to preserve photorealism. Using the single pair of photos available as input, we train a pair of deep convolution networks (convnets), each of which transfers the style of one photo to the other. To enforce photorealism, we introduce a content preserving mechanism by combining a cycle-consistency loss with a self-consistency loss. Exper- imental results show that this method does not suffer from typical artifacts observed in methods working in the same settings. We then further analyze some properties of these trained convnets. First, we notice that they can be used to stylize other unseen images with same known style. Second, we show that retraining only a small subset of the network parameters can be sufficient to adapt these convnets to new styles.