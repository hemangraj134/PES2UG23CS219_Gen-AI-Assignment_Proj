# NLP Summarizer: AI-Powered "TL;DR" News Agent 🚀

### **Project Overview**
This project was developed for **Unit 1 - Project 1 (GenAI & NLP)**. It utilizes Hugging Face's state-of-the-art Transformers library to create a productivity tool that automatically condenses long news articles into concise, meaningful summaries.

### **Key Features**
* **Model:** `sshleifer/distilbart-cnn-12-6` (Distilled BART).
* **Technique:** Abstractive Summarization (rephrasing for human-like flow).
* **Optimization:** Uses **Beam Search (`num_beams=4`)** and **CUDA Acceleration** for high-quality, high-speed output.

### **Tech Stack**
* **Language:** Python 3.x
* **Libraries:** `transformers`, `torch`
* **Hardware:** Optimized for NVIDIA CUDA-enabled GPUs.

### **How to Run**
1. Clone this repository.
2. Open `Unit1-Submission2-Project1.ipynb` in Jupyter or Google Colab.
3. Install dependencies: `pip install transformers torch`
4. Run all cells to see the AI generate a summary for the provided Mars exploration news text.

### **Technical Observation**
By implementing `early_stopping=True` and tuning the beam search parameters, the model successfully avoids truncated "cliffhanger" sentences, providing a logically complete summary that maintains 100% factual accuracy.

---
**Developed by:** Hemang Raj
