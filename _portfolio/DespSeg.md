---
title: "DespSeg"
excerpt: "Jointly reduce speckle noise and segment retinal layers in Vis-OCT images <br/><img src='https://tianyiye98.github.io/page/portfolio/Archi.jpg'>"
collection: portfolio
---
We plan to present the first Vis-OCT retinal image dataset, including retinal boundary annotation and noisy-clean pairs.
<br/><img src='https://tianyiye98.github.io/page/portfolio/Dataset.png'>

Taking advantage of the co-learning process, DespSeg outperforms other self-supervised denoising method(N2V), visually restoring more detials and improving contrast, and improve segmentation performance compared the baseline UNet and sequential strategy. See the more [details](https://tianyiye98.github.io/page/files/paper3.pdf) here. 


<br/>**Fig. 1** Architecture of DespSeg
<img src='https://tianyiye98.github.io/page/portfolio/Archi.jpg'>


<br/> **Fig. 2** Overall denoising and segmentation visualization. Four test samples are displayed, for sample x: (ax) is the clean ground truth, (bx) is the noisy input, (cx) is the N2V denoised image, (dx) is the DespSeg denoised image, (ex) is manually segmentation mask, (fx),(gx),(ex) are the predicted segmenatation masks using UNet with noisy input, using UNet with noisy image denoised by N2V, and using DespSeg with noisy input, respectively.

<br/><img src='https://tianyiye98.github.io/page/portfolio/overall_2.png'>



