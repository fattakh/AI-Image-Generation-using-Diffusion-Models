AI Image Generation using Diffusion Models

This project showcases how to generate stunning AI-generated images from text prompts using Stable Diffusion v1.5 and Hugging Face Diffusers. Diffusion models begin with random noise and gradually refine it into a clear image, guided by your text input.

They are widely used for AI art, realistic image synthesis, creative design, and video generation.

🚀 Features

Text-to-image generation with Stable Diffusion v1.5

Works on GPU (CUDA), Apple Silicon (MPS), and CPU

High-quality image sampling using Euler Ancestral Scheduler

Supports negative prompts to filter unwanted artifacts

Reproducible results with manual seeding

🛠️ Installation

Install the required dependencies:

diffusers

transformers

accelerate

torch & torchvision

safetensors

⚡ Workflow

Set up the pipeline → Load the Stable Diffusion model and detect your hardware (GPU/CPU/MPS).

Define your prompts → Describe what you want and specify what you don’t want (negative prompts).

Generate the image → Fine-tune quality with parameters like inference steps, guidance scale, and random seeds.

Save the result → Export as .png or any format of your choice.

⚙️ Key Parameters

num_inference_steps → Controls detail and refinement (higher = more detail, slower).

guidance_scale → Adjusts how strictly the model follows your text prompt.

seed → Ensures reproducibility; change it for new variations.
