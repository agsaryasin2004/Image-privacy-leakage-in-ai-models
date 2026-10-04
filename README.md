# Image-privacy-leakage-in-ai-models
Academic Project investigation image privacy leakage in AI models and evaluating privacy preseving techniques by creating AI model 
# Image Privacy Leakage in AI Models

## Overview

Academic cybersecurity project investigating gradient leakage and image reconstruction in AI systems. A baseline pipeline was compared with a defended pipeline using face pixelation.


## Methodology

* Developed a proof-of-concept using Python and Google Colab.
* Tested reconstruction of images from leaked model gradients.
* Applied face pixelation as a privacy-preserving measure.
* Compared outputs using MSE, PSNR and SSIM.

## Results

| Metric | Baseline | Face-pixelated defence |
| ------ | -------: | ---------------------: |
| MSE    | 0.042849 |               0.059932 |
| PSNR   | 13.68 dB |               12.22 dB |
| SSIM   |   0.4148 |                 0.2569 |

The defended pipeline produced a less detailed reconstruction. These results suggest that face pixelation reduced the recognisability of the recovered image in this experiment.

## Tools

Python · Google Colab · CNN · Image reconstruction · MSE · PSNR · SSIM

## Limitations

This was a proof-of-concept using a small CNN and a simplified experimental setup. Results do not establish that pixelation prevents all forms of privacy leakage.

## Author

Agsar Yasin — BSc Computer Science in Cyber Security, University of Greenwich
