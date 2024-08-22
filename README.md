# Image-caption-Gen-AI-Project

# Create a Python virtual environment and install Gradio using the following commands in the terminal:
pip3 install virtualenv

virtualenv my_env # create a virtual environment my_env

source my_env/bin/activate # activate my_env

# install required libraries in my_env
pip install langchain==0.1.11 gradio==4.21.0 transformers==4.38.2 bs4==0.0.2 requests==2.31.0 torch==2.2.1

**Tranformers library includes a model that can be used to capture information from images. The BLIP, or Bootstrapping Language-Image Pre-training, model is a tool that helps computers understand and generate language based on images. **


"Blip2Processor" and "Blip2ForConditionalGeneration" are components of the BLIP model, which is a vision-language model available in the Hugging Face Transformers library.

AutoProcessor : This is a processor class that is used for preprocessing data for the BLIP model. It wraps a BLIP image processor and an OPT/T5 tokenizer into a single processor. This means it can handle both image and text data, preparing it for input into the BLIP model.

Note: A tokenizer is a tool in natural language processing that breaks down text into smaller, manageable units (tokens), such as words or phrases, enabling models to analyze and understand the text.

BlipForConditionalGeneration : This is a model class that is used for conditional text generation given an image and an optional text prompt. In other words, it can generate text based on an input image and an optional piece of text. This makes it useful for tasks like image captioning or visual question answering, where the model needs to generate text that describes an image or answer a question about an image.

Python Imaging Library, PIL, is used to open the image file and convert it into an RGB format which is suitable for the model.
