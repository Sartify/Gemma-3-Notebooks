# Gemma-3-Notebooks

This repository contains a collection of Jupyter notebooks demonstrating how to use Google's Gemma 3 models for various natural language processing and multimodal tasks.

## Overview

Gemma 3 is Google's family of lightweight, state-of-the-art open models. These notebooks provide practical examples and implementation guides to help you get started with Gemma 3 for both text-only and multimodal applications.

## Notebooks

## Notebooks and Scripts

The repository includes the following notebooks and scripts:

### [`text_inference_gemma_without_image.ipynb`](scripts/text_inference_gemma_without_image.ipynb)

This notebook demonstrates:
- How to set up and load Gemma 3 models using Hugging Face's Transformers library
- Text-only inference with the Gemma 3 4B instruction-tuned model
- Processing user prompts in a conversational format
- Generating accurate responses for complex tasks (e.g., solving mathematical equations)

### [`text_inference_gemma_with_image.ipynb`](scripts/text_inference_gemma_with_image.ipynb)

This script showcases:
- Multimodal capabilities of Gemma 3 models
- Loading and processing images along with text inputs
- Visual understanding and analysis with Gemma 3
- Handling images from URLs and integrating them into the model prompt
- Using the same conversational format but with image content

## Getting Started

### Prerequisites

- Python 3.8+
- A system with a compatible GPU (recommended)
- Google Colab (for the provided notebooks) or a local Jupyter environment

### Installation

The notebooks contain the necessary installation commands, but in general, you'll need:

```bash
# Install the required dependencies
pip install git+https://github.com/huggingface/transformers@v4.49.0-Gemma-3

# Upgrade and install bitsandbytes for efficient model loading
pip install -U bitsandbytes
```

### Basic Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Gemma-3-Notebooks.git
   cd Gemma-3-Notebooks
   ```

2. Open and run the notebooks in Google Colab or your local Jupyter environment.

3. Follow the step-by-step instructions in each notebook to understand how to work with Gemma 3 models.

## Model Variants

The examples currently focus on:
- `google/gemma-3-4b-it` - The 4 billion parameter instruction-tuned model

You can adapt the examples to use other variants by changing the `model_id` parameter.

## Features

- Text-only inference and generation
- Multimodal capabilities with image and text inputs
- Support for conversational format with system and user messages
- Integration with Hugging Face's Transformers library
- Efficient model loading and inference
- Image loading and processing from URLs

## Future Additions

- Fine-tuning tutorials
- Batch processing examples
- Deployment guides
- Additional multimodal use cases

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Google for creating and releasing the Gemma 3 models
- Hugging Face for providing the integration with the Transformers library

---

**Note**: This repository is not officially associated with Google. Gemma 3 is a product of Google and is subject to its own licensing terms and conditions.
