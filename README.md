# Object-Replacement-in-Images-using-Stable-Diffusion-Model-

This project demonstrates how to replace an object in an image using a quantized Stable Diffusion 3 model. The implementation includes an automated mask generation process powered by the Segment Anything Model (SAM) and provides seamless object replacement based on a text prompt.

# Features 

- Quantized Model: Utilizes a dynamically quantized Stable Diffusion 3 inpainting pipeline for efficient computation.

- Auto-Mask Generation: Automatically generates a mask for the object or human to be replaced, requiring no manual masking.

- Text-Prompted Object Replacement: Replace objects with new ones by simply describing the desired output in a text prompt.

- Interactive Display: Results are saved and displayed for immediate feedback


# Workflow

- Load the quantized Stable Diffusion 3 inpainting model.

- Automatically generate a mask for the target object based on the input image and prompt.

- Replace the specified object with a new one using Stable Diffusion inpainting.

- Save and display the output image.


# Setup and Installation

Prerequisites

- Python 3.8+
- A GPU-enabled environment (e.g., Google Colab, a local machine with CUDA support)
- Download SAM Weights: Download the SAM model weights (e.g., sam_vit_h_4b8939.pth) and place them in the project directory.

