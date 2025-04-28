# MMM Rendering - Colab Setup

This repository contains a Google Colab notebook to set up and run the [MMM-Demo](https://huggingface.co/spaces/samadi10/MMM-Demo) locally or in a Colab environment.

The MMM-Demo is a project that focuses on **generative media models**, enabling users to generate images, videos, or multimedia content.

## Contents

- `mmm_rendering.ipynb`: Colab notebook to clone the MMM-Demo repository and prepare the environment.

## Setup Instructions

To use the notebook:

1. Open the `mmm_rendering.ipynb` file in [Google Colab](https://colab.research.google.com/).
2. Run all cells sequentially.
3. The notebook will:
   - Check the Python version.
   - Install Git Large File Storage (LFS) if needed.
   - Clone the [MMM repository] (https://github.com/exitudio/MMM).

## Requirements

- Google Colab environment (preferred) or local Jupyter Notebook setup with:
  - Python 3.8+
  - Git
  - Git LFS

### Setting up Ngrok

Ngrok is used to create a secure tunnel and access the running demo via a public URL.

#### Steps:
1. **Create an Ngrok Account**:  
   Go to [https://ngrok.com/](https://ngrok.com/) and sign up for a free account.
   
2. **Get Your Auth Token**:  
   After signing up, find your **authtoken** in the Ngrok dashboard.

3. **Place the Auth Token**:  
   In the notebook, locate the code section where Ngrok is set up.  
   Replace the placeholder with your actual auth token:

## License

This project uses content from the [MMM] (https://github.com/exitudio/MMM). Please refer to their repository for license details.

---
