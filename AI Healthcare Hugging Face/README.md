# 🩺 AI Healthcare Assistant using Hugging Face & Prompt Engineering

An AI-powered Healthcare Assistant built using **Hugging Face Transformers**, **Google Colab**, and **Prompt Engineering** techniques. This project demonstrates how Large Language Models (LLMs) can provide structured, informative, and role-specific healthcare responses through carefully designed prompts.

---

## 📌 Project Overview

This project was developed as part of an assignment on **Hugging Face Models and Prompt Engineering**.

The chatbot can:

* Answer healthcare-related questions.
* Generate structured medical information.
* Summarize clinical notes.
* Produce JSON-formatted outputs.
* Adapt responses based on different user roles (Doctor, Nurse, Medical Student, and Patient).
* Compare the performance of two instruction-tuned language models.

---

## 🚀 Features

* 🤖 AI Healthcare Chatbot
* 🧠 Prompt Engineering Techniques
* 📖 Few-Shot Prompting
* 🔗 Chain-of-Thought Prompting (internal reasoning)
* 📄 Structured JSON Output
* 👨‍⚕️ Role-Based Prompting
* 📊 Model Comparison using Pandas
* 📈 Performance Analysis

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Hugging Face Transformers
* PyTorch
* Pandas
* Matplotlib
* Accelerate
* BitsAndBytes (4-bit Quantization)

---

## 🤖 Models Used

### 1. Meta Llama 3.1 8B Instruct

* High-quality instruction-following model
* Strong reasoning capabilities
* Suitable for complex healthcare queries

### 2. Qwen2.5-1.5B-Instruct

* Lightweight instruction-tuned model
* Fast inference
* Lower memory requirements
* Suitable for resource-constrained environments

---

## 📂 Project Structure

```text
AI-Healthcare-Assistant/
│
├── AI_Healthcare_Assistant.ipynb
├── README.md
├── requirements.txt
└── screenshots/
    ├── chatbot.png
    ├── model_comparison.png
    └── output_examples.png
```

---

## 📊 Prompt Engineering Techniques

The following prompt engineering techniques were implemented:

* Role Prompting
* Context Prompting
* Constraint Prompting
* Few-Shot Prompting
* Chain-of-Thought Prompting
* Structured Output Prompting

---

## 📈 Model Comparison

Both models were evaluated using the same healthcare-related prompts.

Comparison criteria included:

* Response Quality
* Accuracy
* Clarity
* Completeness
* Instruction Following
* Computational Efficiency

The responses were collected and analyzed using **Pandas**, and summary statistics were used to compare overall performance.

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/AI-Healthcare-Assistant.git
```

2. Install the required libraries.

```bash
pip install transformers accelerate bitsandbytes torch pandas matplotlib
```

3. Obtain a Hugging Face access token.

4. Open the notebook in Google Colab.

5. Replace the token with your own Hugging Face token.

6. Run all notebook cells.

---

## 📷 Sample Output

The chatbot can:

* Explain diseases
* Summarize patient notes
* Generate structured JSON
* Answer healthcare-related questions
* Produce role-specific responses for doctors, nurses, students, and patients

---

## 📚 Learning Outcomes

Through this project, I learned:

* Using Hugging Face Transformers
* Loading and running instruction-tuned LLMs
* Prompt Engineering techniques
* Comparing multiple language models
* Working with Pandas for response analysis
* Building AI-powered conversational applications

---

## ⚠️ Disclaimer

This project is intended **for educational purposes only**. The generated responses are **not a substitute for professional medical advice, diagnosis, or treatment**. Always consult a qualified healthcare professional for medical concerns.

---

## 👨‍💻 Author

**Rajeet Mavi**

B.Tech – Computer Science & Engineering (AI & ML)
