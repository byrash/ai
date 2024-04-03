Ollama Start

`ollama serve`

To download any model from Ollama published models

`ollama pull mistral`

Steps to Create Ollama Model from Hugging Faces

1. Download hugging faces model

`huggingface-cli download runwayml/stable-diffusion-v1-5 --local-dir models/ --local-dir-use-symlinks False`

2. Create Ollama model

`ollama create text-to-image -f text_to_image`
