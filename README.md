# OdiaGenAI-4-bit-Bengali-LLM

### bModel
The BengaliGPT model, odiagenAI-bengali-lora-model-v1, was released on 10th June 2023 through Hugging Face with a CC BY-NC-SA 4–0 license. The model is based on Llama-7b as the base model and finetuned with the Bengali translated instruction set with 5 epochs. The Hugging Face model card shows the model descriptions and running instructions. The code (translation, training, and inference) is available on GitHub.

### Inference
The inference script is adapted from Alpaca-LoRA considering the base model Llama-7b with the odiagenAI-bengali-lora-model-v1 weights.

The inference prompt accepts the input in Bengali text and outputs Bengali text — the generated output. The text-to-speech is integrated, so, the output is converted to speech.

![image](https://github.com/zafor158/OdiaGenAI-4-bit-Bengali-LLM/assets/98481506/093943d1-c9d6-4598-9b19-41bab988c99b)
https://miro.medium.com/v2/resize:fit:4800/format:webp/1*x_JOa7wesqwMgvVovxvQXQ.jpeg

