# GenAI
# GPT-2 Text Generator

## Overview
This project utilizes the GPT-2 language model from Hugging Face's `transformers` library to generate text based on an input prompt. By adjusting various parameters, users can control the creativity and style of the generated text.

## Requirements
To run this project, you will need Python 3.6 or higher, along with the following libraries:
- `transformers`
- `torch`

These dependencies can be installed using pip.

## How to Use
1. **Input a Prompt:** The program will ask for a text prompt, which will serve as the starting point for the text generation.
2. **Text Generation:** After entering the prompt, the GPT-2 model generates a continuation of the text based on the provided prompt. The generation process can be customized using parameters like `temperature`, `top-k`, `top-p`, and `repetition penalty`.

## Customization
The text generation process allows for customization:
- **Max Length:** Controls how long the generated text can be.
- **Temperature:** Adjusts the creativity of the model. Lower values result in more conservative outputs.
- **Top-k and Top-p:** These settings influence the diversity of the generated text by limiting the pool of potential next words.
- **Repetition Penalty:** Prevents the model from repeating the same phrases or words too often.

## Example
After providing a prompt, the model will generate text that continues the idea or theme of the prompt. This can be useful for creative writing, brainstorming, or just exploring the capabilities of language models.

## Notes
- The output may vary in quality, and sometimes the generated text might not make perfect sense.
- The model works best with coherent, well-structured prompts.

## License
This project is licensed under the MIT License, allowing for open usage and modification.
