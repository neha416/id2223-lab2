# id2223-lab2
Lab 2: Parameter Efficient Fine-Tuning (PEFT) of a Large Language Model
Task 1: Fine-tune a Model and Create a UI
Overview
In this task, we fine-tuned a pre-trained LLM (Llama-3 1B) using LoRA (Low-Rank Adaptation) on the FineTome Instruction Dataset. The fine-tuning was performed on Google Colab with a Tesla T4 GPU.
The fine-tuned model was saved locally and then used to build a simple chatbot interface using Gradio.
Steps Completed
1.	Setup Environment
○	Installed required libraries including unsloth, transformers, and gradio.
○	Verified GPU availability (Tesla T4).
2.	Fine-Tuning
○	Loaded pre-trained LLaMA-3 1B model.
○	Applied LoRA for parameter-efficient fine-tuning.
○	Trained the model on the FineTome Instruction Dataset for a few epochs.
○	Saved the fine-tuned model locally as lora_model.
3.	Gradio UI
○	Created a simple web interface where users can input text and get responses from the fine-tuned model.
○	The interface runs in Colab and can be optionally hosted on Hugging Face Spaces.
Results
●	The model is capable of responding to text prompts using knowledge from the FineTome Instruction Dataset.
●	Peak GPU memory usage and training runtime were monitored and saved (details available in notebook outputs).
Notes
●	This setup demonstrates parameter-efficient fine-tuning and basic inference using a simple UI.
●	For higher grades, additional improvements such as multi-model comparison or advanced UI are optional.

