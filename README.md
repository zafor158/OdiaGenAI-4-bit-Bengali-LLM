# OdiaGenAI-4-bit-Bengali-LLM

### bModel
The BengaliGPT model, odiagenAI-bengali-lora-model-v1, was released on 10th June 2023 through Hugging Face with a CC BY-NC-SA 4–0 license. The model is based on Llama-7b as the base model and finetuned with the Bengali translated instruction set with 5 epochs. The Hugging Face model card shows the model descriptions and running instructions. The code (translation, training, and inference) is available on GitHub.

### Inference
The inference script is adapted from Alpaca-LoRA considering the base model Llama-7b with the odiagenAI-bengali-lora-model-v1 weights.

The inference prompt accepts the input in Bengali text and outputs Bengali text — the generated output. The text-to-speech is integrated, so, the output is converted to speech.

![image](https://github.com/zafor158/OdiaGenAI-4-bit-Bengali-LLM/assets/98481506/093943d1-c9d6-4598-9b19-41bab988c99b)
![image](https://github.com/zafor158/OdiaGenAI-4-bit-Bengali-LLM/assets/98481506/cee0c580-7ba0-4db5-9289-fcb96a73b525)
![image](https://github.com/zafor158/OdiaGenAI-4-bit-Bengali-LLM/assets/98481506/171ce5ef-fe49-492b-93cc-5396855d44b6)

### How to Use
Bengali Generative AI has just released its latest model, and the best part is that anyone can now access and use it on Colab, free of charge! This powerful language model is trained to generate text in the Bengali language, allowing users to create Bengali content, generate creative writing, or even build Bengali language-based applications.

But that’s not all. The Bengali Generative AI’s latest model also comes with an integrated Text-To-Speech (TTS) feature. This means that not only can you generate text in Bengali, but you can also have that text converted into natural-sounding speech. It opens up a whole new range of possibilities for audio content creation, language learning, accessibility, and more. Running the model on Colab is a breeze.

### Just follow these simple steps:
 Step1: Open the link to the Bengali Generative AI model on Colab: [https://colab.research.google.com/drive/1HYHZJwsNWk9auZ_o39G3AIGMtGkqVG2o?usp=sharing].
Step 2: In Colab, navigate to “Runtime” and select “Run all cells”. This will initiate the model and load all the necessary dependencies.
Step 3: Once the cells have finished running, you will be provided with a Gradio URL. Gradio is a user-friendly interface that allows you to interact with the model effortlessly.
Step 4: Click on the Gradio URL, and it will open a web interface where you can input your desired text in Bengali

![image](https://github.com/zafor158/OdiaGenAI-4-bit-Bengali-LLM/assets/98481506/fb14e87d-b815-4ab7-9c8d-23f70bcc758e)
You can choose to generate text or have it converted into speech using the integrated TTS feature. Play around with the model, generate Odia text, and listen to the TTS output. Explore its capabilities and get creative with your ideas.

### Analysis
Although the current model is able to accept Bengali input text and generate answers in Bengali, it still fails to answer questions related to general knowledge about India due to a lack of domain knowledge. Also, it fails in critical reasoning as per evaluation.

### Future Plan
The plan includes 
i) fine-tuning with a more domain-specific Bengali instruction set.
ii) Pre-train Bengali LLM model.
and iii) Chatbot development supporting Bengali.




