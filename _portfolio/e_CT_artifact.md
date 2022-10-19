---
title: "Sparse-view artifacts reduction in CT image"
excerpt: "Unsupervised learning based on CycleGAN compared to supervised ResNet and UNet<br/><img src='https://tianyiye98.github.io/page/portfolio/CT_artifact_reduction.png'>"
collection: portfolio
---

I implemented CycleGAN to perform unsupervised metal/sparse-view artifact reduction and compared sparse-view artifact reduction performance 
with the supervised methods ResNet50 and UNet. The sparse-view artifacts degrade image quality more severely than metal artifacts, explaining the
unsatisfactory result of CycleGAN compared to supervised method. Combining both projection domain and image domain for such task is necessary since 
the image has lost too much information. 


<br/>**Fig. 1** Synthesized video with detected landmarks
<br/><img src='https://tianyiye98.github.io/page/portfolio/CT_artifact_reduction.png'>



