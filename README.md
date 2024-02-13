# Contrastive-VS-Captioning-Image-Pretraining
Exploring the impact of pretraining approaches on image classification effectiveness of contrastive and captioning trained models.


## Description
⚠️ **This is just a short "experiment" to be continued in the future** ⚠️
This experiment aims to answer the question: **"Is it better to pretrain using contrastive learning or image captioning?"** (when having a image-text paired dataset)
This repository documents an exploratory **study comparing the effectiveness of contrastive and captioning pretraining approaches for image classification tasks**. Using the Caltech 256 and Oxford 102 flowers datasets, we trained a single linear layer classification head on the outputs pooled from two distinct image encoder models: CLIP (with contrastive training) and BLIP (with captioning training). Both encoders utilize the ViTB16 architecture and were kept frozen during our experiments. This initial foray, conducted over 10 epochs, seeks to uncover which pretraining method better serves downstream image classification tasks.

The primary goal of this experiment is not to produce state-of-the-art results but to initiate a discussion and provide preliminary insights into whether contrastive or captioning pretraining offers more promise for enhancing the capabilities of image classification models.


## Methodology
- Models Used: CLIP (Contrastive Language–Image Pretraining) and BLIP (Bootstrapped Language Image Pretraining), both employing the ViTB16 architecture.
- Training Data: Caltech 256 and Oxford 102 flowers datasets.
- Procedure: The models' pretrained weights were kept frozen, and only a single linear classification layer was trained for each setup.
- Epochs: 10, to establish an initial understanding of each pretraining approach's potential.

## Reults

