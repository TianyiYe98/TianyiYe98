---
title: "DenoiSegOCT"
excerpt: "Simultaneous Noise Reduction and Layer Segmentation for Visible Light Optical Coherence Tomography in Human Retina 
<br/><img src='https://tianyiye98.github.io/page/portfolio/dataset_1.png'>"
collection: portfolio
---
We plan to present the first Vis-OCT retinal image dataset, including retinal boundary annotation and noisy-clean pairs.
<br/>**Fig. 1** Retinal boundary delineation, individually reviewed and edited. 
<br/><img src='https://tianyiye98.github.io/page/portfolio/Dataset.png'>

<br/>**Fig. 2** Noisy-clean pairs and retinal boundary delineation
<br/><img src='https://tianyiye98.github.io/page/portfolio/dataset_1.png'>


<br/>Given the qualitative and quantitative results, our framework achieves considerable performance with self-denoising and segmentation baselines and provides an angle for few-shot or small dataset learning of segmentation, which is common in many clinical scenarios. See the more [details](https://tianyiye98.github.io/page/files/DenoiSegOCT_bioRxiv_v1.pdf) here.


<br/>**Fig. 2** Architecture of DenoiSegOCT
<img src='https://tianyiye98.github.io/page/portfolio/Archi.jpg'>


<br/> **Fig. 3** Overall denoising visualization with 50% annotation and segmentation visualization with 25% annotation. Two test samples are displayed. For a sample x: (ax) is the clean ground truth, (bx) is the noisy input, (cx) is the N2V denoised image, (dx) is the DenoiSegOCT denoised image, (ex) is the manual segmentation mask, (fx),(gx),(hx) are the predicted segmentation masks using ours without denoising, using UNet with image denoised by N2V, and using ours with denoising, respectively.
<br/><img src='https://tianyiye98.github.io/page/portfolio/visualization_1.png'>



