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


<br/> **Fig. 3** Overall denoising and segmentation visualization using noisy input with 25% annotation. Two test samples aredisplayed. For a sample x: (ax) is the clean ground truth, (bx) is the noisy input, (cx) is the N2V denoised image, (dx) is the DespeckSeg denoised image, (ex) is the manual segmentationmask, (fx),(gx),(hx) are the predicted segmentation masks using ours without denoising, using UNet with image denoisedby N2V, and using ours with denoising , respectively.

<br/><img src='https://tianyiye98.github.io/page/portfolio/overall_1.png'>



