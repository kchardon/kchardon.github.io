---
title: "Reliability of cerebellar volumetry : a test / re-test study"
collection: talks
type: "Poster"
permalink: /presentations/2025-07-06-cerebellum_grc
venue: "Cerebellum GRC 2025"
date: 2025-07-06
location: "Les Diablerets, Switzerland"
---
‎

## Abstract

The cerebellum participates in cognitive and motor functions, and is involved in psychiatric disorders such as schizophrenia and autism. Accurate and reliable quantification of its structure is an unmet need because the cerebellum's foliated structure and fine subregional organization present significant challenges for automated parcellation.

Several tools, including traditional atlas-based approaches and recent deep learning methods, have been developed to segment and parcellate the cerebellum. While these tools are typically evaluated based on segmentation accuracy, their test-retest reliability, essential for longitudinal and individual difference studies, has not yet been compared.

In this study, we assessed the test-retest reliability of four cerebellar segmentation pipelines: SUIT-VBM, ACAPULCO, CERES, and DeepCERES. We used high-resolution T1-weighted images from the Hangzhou Normal University open dataset, which includes 10 MRI sessions for 11 healthy participants (5 females, 6 males, mean age 24.1 ± 2.7 years) scanned every three days over one month. Volumes of cerebellar subregions were extracted from each method, normalized by intracranial volume to account for head size, and scaled across lobules to correct for size differences. We then computed intra-individual variability, inter-individual variability, and intraclass correlation coefficients (ICC) using the ReX toolbox.

All pipelines demonstrated strong test-retest reliability, with average ICC values above 0.80. DeepCERES showed the most robust performance, exhibiting high ICC, high inter-individual reliability, and low intra-individual reliability. Statistical comparisons revealed significantly greater reliability for DeepCERES than ACAPULCO (p < 0.05). Lobules X and VIIIB showed a lower reliability across methods, imposing particular attention when evaluating these subregions and interpreting results. 

These findings inform the state-of-the-art in AI-based cerebellum parcellation and will help in achieving and interpreting clinical and developmental research results.


## Resources

- [Poster (PDF)](/files/posterV5_CerebellumGRC_Chardon_.pdf)