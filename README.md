# Fine-Tuning GPT-2 on Harry Potter Dialogues

## 🎯 Objective
Fine-tune GPT-2 on a small domain dataset (Harry Potter dialogues) and compare:
- Few-shot prompting (no fine-tuning)
- Fine-tuned model performance

## 📚 Dataset
- Dataset: Harry Potter and the Philosopher’s Stone script
- Download link: https://www.kaggle.com/datasets/eward96/harry-potter-and-the-philosophers-stone-script

## ⚙️ Instructions
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
2.	Run the notebook hp_gpt2_finetuning.ipynb.
3.	Outputs:
o	Fine-tuned model saved under fine_tuned_model/
o	Sample text generations in sample_generations_before_after.txt
