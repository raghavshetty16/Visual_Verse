# Stable Diffusion v1-5 AI Image Generator

## Overview
This project utilizes the Stable Diffusion v1-5 model by RunwayML to generate images from text prompts. The model is based on a latent diffusion framework and can produce high-quality images by interpreting and transforming textual descriptions.

## Features
- **Model Name**: stable-diffusion-v1-5
- **Model Type**: Diffusion-based text-to-image generation
- **Customizable Prompts**: Generate images by simply providing a text prompt.
- **Negative Prompting**: Improve image quality by specifying undesirable features to avoid.

## Installation

### Requirements
- Python 3.7+
- GPU with CUDA support (for faster processing)

### Dependencies
Install the necessary packages using pip:
- `diffusers`
- `transformers`
- `gradio==3.48.0`

## Usage
1. Load the necessary libraries and the Stable Diffusion model.
2. Define a function to generate images from prompts.
3. Launch a user-friendly web interface for image generation.

## Example Prompts
- "baby llama, wearing red muffler, grazing, open field, sunset"
- "children, playing in disneyland, view from a distance"

## References
- [Stable Diffusion v1-5 Model](https://huggingface.co/runwayml/stable-diffusion-v1-5)
- [Diffusers Documentation](https://huggingface.co/docs/diffusers/index)
