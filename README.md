# Fine-Tuning LLaMA 2 with Hugging Face  

This project demonstrates how to fine-tune a **LLaMA 2** model using **Hugging Face’s TRL (Transformers Reinforcement Learning)** and **PEFT (Parameter-Efficient Fine-Tuning)** libraries.  
The model was trained on a dataset of **medical terms** and produces specialized text outputs for medical-related prompts.  

---

## Project Overview  
- **Model**: Fine-tuned from *LLaMA 2* using LoRA (Low-Rank Adaptation).  
- **Libraries**: Hugging Face Transformers, TRL, PEFT, Accelerate, BitsAndBytes.  
- **Dataset**: Medical terms in LLaMA-2 format.  
- **Goal**: Efficient fine-tuning of a large language model to answer domain-specific questions.  

---

## Example Usage  

**Prompt:**  
<s>[INST] Please tell me about Ascariasis [/INST]

**Model Output (example):** 
Ascariasis is a parasitic infection caused by the Ascaris lumbricoides roundworm, which is the most common intestinal parasite in the world. everybody gets infected with Ascaris at some point in their lifetime, but most people don't exhibit any symptoms. However, in some cases, the infection can cause a range of health problems, including:

1. Abdominal pain: Ascaris infection can cause abdominal pain, which can be mild to severe.
2. Diarrhea: Ascaris infection can lead to diarrhea, which can be accompanied by blood in the stool.
3. Weight loss: Ascaris infection can cause weight loss due to malabsorption of nutrients.
4. Anemia: Ascaris infection can lead to anemia due to the absorption of iron from the host's body.
5. Obstruction: Ascaris infection can cause intestinal obstruction, which can lead to vomiting, abdominal pain, and constipation.
6. Intestinal perforation: Ascaris infection can cause intestinal perforation, which can lead to peritonitis and death.
7. Eos

---

## Running the Notebook in Colab  

You can run and reproduce the fine-tuning process in **Google Colab** without local setup.  
Click the button below to create your own copy of the notebook directly from this repository:  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Connor2452/Tuned-Llama-2-Chatbot/blob/main/Fine_Tuning_LLMs_with_Hugging_Face.ipynb#scrollTo=copy)
---

## 📂 Repository Structure  
- Fine_Tuning_LLMs_with_Hugging_Face.ipynb # Colab notebook for fine-tuning and inference
- README.md # Project documentation
- fine_tuning_llms_with_hugging_face.py # Same file but in .py format

  ## Note
  - This project was made in Colab and is intended to run in that enviroment, if trying to recreate results other packages may be required
