## Session 1: Prompt Engineering

### Assignment 1: Zero-shot vs Few-shot Prompting
**Objective:**  
Understand the difference between zero-shot and few-shot prompting in LLMs.

**Description:**  
- **Zero-shot prompting**: Provided the model with only the instruction, no examples.  
- **Few-shot prompting**: Provided the model with a few examples before the task instruction.  
- Compared outputs to analyze performance differences.

---

### Assignment 2: Role-based & Chain-of-Thought Prompting
**Objective:**  
Learn how role-based and chain-of-thought prompting improve response quality.

**Description:**  
- **Role-based prompting**: Assigned a specific role to the model to get contextually aligned answers.  
- **Chain-of-Thought prompting**: Asked the model to think step-by-step for better reasoning.  
- Tested on both creative and reasoning-based tasks.

---

## Session 2: Open Source LLMs & Local Setup

### Assignment 1: Hugging Face Model Exploration
# 📰 News Summarizer with Highlights

## 📌 Description
This Streamlit application allows users to paste any news article and instantly get:
1. **A concise AI-generated summary** using a Hugging Face `t5-small` summarization model.
2. **Key highlights** (Named Entities) extracted using the `dslim/bert-base-NER` model, grouped by type (e.g., PERSON, LOCATION, ORGANIZATION).

The app leverages **PyTorch** for hardware acceleration and automatically runs on **GPU** if available for faster processing.
<img width="1920" height="1341" alt="screencapture-localhost-8501-2025-08-14-12_31_28" src="https://github.com/user-attachments/assets/2b70b70b-171c-4e81-91f7-77e1502a3c29" />


---

### Assignment 2: Local LLM Installation and Testing
**Objective:**  
Install and run a local LLM to evaluate performance.

**Description:**  
- Installed Ollama LLaMA 3.2 locally.  
- Ran a test prompt: “Write a short poem about AI.”  
- Measured response time.  

---

## Session 3: Calling LLM via Python Code

**Features**
- Text Generation Script – Accepts a prompt and generates AI responses.
- Chat Script – Multi-turn conversation with context retention.
- Streaming Output – Real-time token-by-token display of responses.
- Error Handling – Retries, exception management, and fallback logic.
- Configurable Parameters – Model, temperature, and max tokens adjustable from UI.
- Logging & Caching – Faster repeated runs and debug-friendly logs.
- Clean UI – Minimal Streamlit interface for ease of use.
<img width="1920" height="1230" alt="screencapture-localhost-8501-2025-08-15-18_11_29" src="https://github.com/user-attachments/assets/819169f9-ebf9-4e6d-928c-57c554fece1d" />
<img width="1920" height="2642" alt="screencapture-localhost-8501-2025-08-15-18_12_42" src="https://github.com/user-attachments/assets/1cbf3a78-cf2d-48bc-ae60-11d3be58b494" />

