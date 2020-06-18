---
title: "Semantic Example Guided Image-to-Image Translation"
collection: publications
permalink: /publication/segin
excerpt: 'This paper is a self-supervised method to achieve semantic example guided image-to-image translation.'
date: 2020-06-15
venue: 'IEEE Transactions on Multimedia'
paperurl: 'https://arxiv.org/abs/1909.13028'
#citation: ''
---
__Abstract__
Many image-to-image (I2I) translation problems are in nature of high diversity that a single input may have various counterparts. The multi-modal network that can build many-to-many mapping between two visual domains has been proposed in prior works. However, most of them are guided by sampled noises. Some others encode the reference images into a latent vector, by which the semantic information of the reference image are washed away. In this work, we aim to provide a solution to control the output based on references semantically. Given a reference image and an input in another domain, we first perform semantic matching between the two visual content and generate the auxiliary image, which explicitly encourages the semantic characteristic to be preserved. A deep network then is used for I2I translation and the final outputs are expected to be semantically similar to both the input and the reference. However, few paired data can satisfy that dual-similarity in a supervised fashion, and so we build up a self-supervised framework to serve the training purpose. We improve the quality and diversity of the outputs by employing non-local blocks and multi-task architecture. We assess the proposed method through extensive qualitative and quantitative evaluations and also present comparisons with several state-of-the-art models.  
[Download pdf here](http://academicpages.github.io/files/paper1.pdf)
