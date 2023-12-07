<h1 align="center">Fast-Processing Bi-Modal Large Language and Vision Model</h1>

<p align="center"><strong>Author:</strong> Rugved Chavan</p>

## Overview
This repository explores the intersection of different AI modalities, particularly focusing on text and image generation. Our research delves into the intricacies of generative AI, leveraging advanced algorithms and data availability to push the boundaries of what's possible in AI-driven content creation.

<p align="center">
  <img src="Image.png" alt="Research Image">
</p>

## Abstract
Recently, Generative AI has gained popularity due to an increase in data availability, advanced algorithms, and the wider accessibility of generative AI tools. Sophisticated algorithms, such as attention mechanisms like Transformers for text generation and UNet for diffusion models in image generation, as well as audio channels with a single channel mel-spectrogram, are contributing factors. Additionally, pseudo-temporal attention mechanisms are utilized for video generation. There has been substantial research in each modality—image, video, audio, text—aiming to emulate human-like understanding, reasoning skills, and creativity. Concurrently, there is parallel research focused on creating multi-modality models capable of generating paired content across various formats. Notably, Microsoft's Composible Diffusion CoDi has developed a model for simultaneously processing an arbitrary combination of information. In our independent study, the primary objectives were to gain a thorough understanding of each modality and to comprehend how the CoDi model architecture integrates them. Moreover, we investigated the inference time and content quality of the CoDi model, proposing an improved architecture. Furthermore, we will develop a Bi-modality model [Text, Image] to demonstrate our hypothesis of enhanced performance based on a pretrained model, rather than starting from scratch. Utilizing core technologies such as CLIP, GPT-2 LLM, Stable Diffusion UNet, and Diffusion VAE Decoders, this model will eliminate the requirement to specify which output modality needs to be activated, unlike CoDi.

## Video Overview

<p align="center">
  <a href="http://www.youtube.com/watch?v=bDb0FkX1tLI">
    <img src="http://img.youtube.com/vi/bDb0FkX1tLI/0.jpg" alt="Video Overview">
  </a>
</p>

<p align="center">
  <em>Click on the image above to watch the video.</em>
</p>

Download the `model.h5` file from Google Drive: [Download Model](https://drive.google.com/file/d/1u53HryRB4cXAt3rtpu0zx1tJvkAmGHXm/view?usp=sharing)


## References
1. Transformers for Text Generation
2. UNet for Diffusion Models
3. Microsoft's Composible Diffusion CoDi
