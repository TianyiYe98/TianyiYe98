---
title: "DespeckSeg"
excerpt: "Jointly reduce speckle noise and segment retinal layers in Vis-OCT images <br/><img src='https://tianyiye98.github.io/page/portfolio/Archi.jpg'>"
collection: portfolio
---
We plan to present the first Vis-OCT retinal image dataset, including retinal boundary annotation and noisy-clean pairs.
<br/>**Fig. 1** Retinal boundary delineation, individually reviewed and edited. 
<br/><img src='https://tianyiye98.github.io/page/portfolio/Dataset.png'>



<br/>Taking advantage of the co-learning process, DespeckSeg outperforms other self-supervised denoising method(N2V), visually restoring more detials and improving contrast, and improve segmentation performance compared the baseline UNet and sequential strategy. See the more [details](https://tianyiye98.github.io/page/files/DespeckSeg.pdf) here. 


<br/>**Fig. 2** Architecture of DespeckSeg
<img src='https://tianyiye98.github.io/page/portfolio/Archi.jpg'>


<br/> **Fig. 3** Overall denoising and segmentation visualization. Four test samples are displayed, for sample x: (ax) is the clean ground truth, (bx) is the noisy input, (cx) is the N2V denoised image, (dx) is the DespeckSeg denoised image, (ex) is manually segmentation mask, (fx),(gx),(ex) are the predicted segmentation masks using UNet with noisy input, using UNet with image denoised by N2V, and using DespeckSeg with noisy input, respectively. Note that this visualization does not represent the trend of the quantitative result. For representative visualization see the [draft](https://tianyiye98.github.io/page/files/DespeckSeg.pdf).

<br/><img src='https://tianyiye98.github.io/page/portfolio/overall_2.png'>



