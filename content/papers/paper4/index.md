---
title: "Generative AI for rapid diffusion MRI with improved image quality, reliability, and generalizability" 
date: 2024-06-13
author: ["Amir Sadikov", "Xinlei Pan", "Hannah L Choi", "Lanya T Cai", "Pratik Mukherjee"]
summary: "We employ a SWIN model, trained on HCP data and conditioned on registered T1 scans, to perform generalized dMRI denoising with DTI requiring only 90 seconds of scan time." 
cover:
    image: "paper4.png"
    alt: "diffusion MRI denoising"
    relative: true
    
---

##### Download

+ [Paper](https://direct.mit.edu/imag/article/doi/10.1162/imag_a_00193/121200/Generative-AI-for-rapid-diffusion-MRI-with)
+ [Preprint](https://arxiv.org/abs/2303.05686)
+ [Code and Data](https://github.com/ucsfncl/dmri-swin)

---

##### Abstract

We use generative AI to enable rapid diffusion MRI (dMRI) with high fidelity, reproducibility, and generalizability across clinical and research settings. We employ a Swin UNEt Transformers (SWIN) model, trained on Human Connectome Project (HCP) data (n = 1021) and conditioned on registered T1 scans, to perform generalized dMRI denoising. We also qualitatively demonstrate super-resolution with artificially downsampled HCP data. Remarkably, SWIN can be fine-tuned for an out-of-domain dataset with a single example scan, as we demonstrate on dMRI of children with neurodevelopmental disorders (n = 40), adults with acute traumatic brain injury (n = 40), and adolescents with intracerebral hemorrhage due to vascular malformations undergoing resection (n = 8), each cohort scanned on different scanner models with different imaging protocols at different sites. This robustness to scan acquisition parameters, patient populations, scanner types, and sites eliminates the advantages of self-supervised methods over our fully supervised generative AI approach. We exceed current state-of-the-art denoising methods in accuracy and test–retest reliability of rapid diffusion tensor imaging (DTI) requiring only 90 seconds of scan time. SWIN denoising also achieves dramatic improvements over the state-of-the-art for test–retest reliability of intracellular volume fraction and free water fraction measurements and can remove heavy-tail noise, improving biophysical modeling fidelity. SWIN enables rapid diffusion MRI with unprecedented accuracy and reliability, especially at high diffusion weighting for probing biological tissues at microscopic spatial scales. The code and model are publicly available at https://github.com/ucsfncl/dmri-swin.

