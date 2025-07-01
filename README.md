# 🎨 gst-image-generation-techniques

## 1. 🤖 SD, FLUX, and Hidream lora finetuning

### 🏋️ Fluxgym
[Fluxgym](https://github.com/cocktailpeanut/fluxgym)

### 🎯 sd-lora-trainer
[sd-lora-trainer](https://github.com/edenartlab/sd-lora-trainer/)

### 🛠️ OneTrainer
[OneTrainer](https://github.com/Nerogar/OneTrainer)

### 💎 Hidream
[Hidream](https://github.com/HiDream-ai/HiDream-I1)

HiDream-I1 is a new open-source image generative foundation model with 17B parameters that achieves state-of-the-art image generation quality within seconds.

[comfyui_HiDream-Sampler](https://github.com/lum3on/comfyui_HiDream-Sampler)

Full/Dev/Fast requires roughly 27GB VRAM  
NF4 requires roughly 15GB VRAM

### 🌊 Stable Cascade
[stable-cascade](https://github.com/Stability-AI/StableCascade)

[stable-cascade workflow and guide](https://civitai.com/articles/4253/stable-cascade-lora-training-with-onetrainer)

## 2. 📝 Image to Text Annotation

Image to text or text to image annotation can be done in a variety of ways, and can be optimized with automations, but none of these beat out good old human annotations. Fluxgym and Onetrainer above offer built in annotation systems using the google florence image to text vision model for fluxgym and I will update this when I find what vision model onetrainer uses. Below you will find my image annotation ui that i built which is a little more capable than fluxgym in that it allows you to export and import your datasets easily, and offers automatic annotation with ollama gemma3:4b vision which can be improved by modifying the system prompt and finetuning a gemma3:4b vision lora with unsloth.

[oarc-image-annotation-ui](https://github.com/Ollama-Agent-Roll-Cage/oarc-image-annotation-ui)

## 3. 🔗 Lora Merging and Base model fusion

[Merge LoRAs HF](https://huggingface.com/docs/diffusers/main/using-diffusers/merge_loras)

This guide will show you how to merge LoRAs using the set_adapters() and add_weighted_adapter methods. To improve inference speed and reduce memory-usage of merged LoRAs, you'll also see how to use the fuse_lora() method to fuse the LoRA weights with the original weights of the underlying model.

[Merge-Diffusion-Tool](https://github.com/itspranavajay/Merge-Diffusion-Tool)

Solution for merging LoRA models, integrating LoRA into checkpoints, and blending Flux And Stable Diffusion models (SD1.5, SD2, SD3, SDXL). Optimize your AI workflows with ease.

## 4. ⭐ A collection of my favorite finetunes

[latent-consistency/lcm-sdxl](https://huggingface.co/latent-consistency/lcm-sdxl)

[Popyay's Epic Fantasy Style](https://civitai.com/models/470073?modelVersionId=560995)

[Zavy's Chromatic Blur - SDXL](https://civitai.com/models/385965/zavys-chromatic-blur-sdxl)

[Randommaxx Art Merge](https://civitai.com/models/368498/randommaxx-art-merge)

[Transparent Glass Body](https://civitai.com/models/196040/transparent-glass-body-lora-15sdxl)

[Aether Aqua - LoRA for SDXL](https://civitai.com/models/210754/aether-aqua-lora-for-sdxl)

[Aether Fire - LoRA for SDXL](https://civitai.com/models/157594/aether-fire-lora-for-sdxl)

[Aether Pixel - LoRA for SDXL](https://civitai.com/models/197757/aether-pixel-lora-for-sdxl)

[Aether Cloud - LoRA for SDXL](https://civitai.com/models/141029/aether-cloud-lora-for-sdxl)

[Aether Ghost - LoRA for SDXL](https://civitai.com/models/133412/aether-ghost-lora-for-sdxl)

[Fjsmu | Style LoRa](https://civitai.com/models/1184962?modelVersionId=1333808)

## 5. 🖼️ Comfyui workflow collection for SDXL and FLUX
***COMING SOON***

=====================================

# 🎮 Game Dev Techniques
***COMING SOON***

## 6. 🎨 Pixelator workflow and guide

=====================================

## 7. 🏔️ Perlin noise Terrain Generation Guide

=====================================

## 8. 🎯 2D pixel Sprites from 3D models at isometric perspective

=====================================

## 9. 🧠 CANs and GANs: Pix2Pix, CycleGAN, StyleGAN, and any others that are applicable at the time.

=====================================

## 10. 📚 other

[The Annotated Diffusion Model](https://huggingface.co/blog/annotated-diffusion)
