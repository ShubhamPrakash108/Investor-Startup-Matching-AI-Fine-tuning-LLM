# 🧠 Fine-Tuning Falcon-RW-1B for Investor-Startup Conversations

This project fine-tunes the [Falcon-RW-1B](https://huggingface.co/tiiuae/falcon-rw-1b) language model to simulate realistic conversations between investors and startups. It includes custom data generation, model training, and inference pipelines.

## 📁 Project Structure

```bash
.
├── data-generation.ipynb                # Notebook for synthetic dataset creation
├── investor-startup-fine-tuning-falcon-rw-1b.ipynb  # Notebook to fine-tune Falcon-RW-1B
├── Fine_tuned_model_inference.ipynb     # Notebook to run inference using the fine-tuned model
```

---

## 📊 Objective

To create a dialogue model capable of understanding and responding to investor and startup-specific queries by:

* Generating structured, domain-relevant training data
* Fine-tuning a pretrained Falcon model on that data
* Testing the model's performance on unseen dialogue prompts

---


## Run Notebooks

* `data-generation.ipynb`: Generates synthetic Q\&A pairs for training.
* `investor-startup-fine-tuning-falcon-rw-1b.ipynb`: Fine-tunes the model using PEFT & LoRA.
* `Fine_tuned_model_inference.ipynb`: Loads and evaluates the trained model.

---

## 🧠 Model Details

* **Base Model**: Falcon-RW-1B from Hugging Face
* **Fine-Tuning Method**: LoRA (Low-Rank Adaptation) with PEFT
* **Training Data**: Synthetic conversations mimicking investor-startup interactions

---

## 📌 Key Features

* Modular pipeline for quick adaptation to other domains
* Efficient training with parameter-efficient techniques
* Easy-to-use inference notebook with sample prompts

