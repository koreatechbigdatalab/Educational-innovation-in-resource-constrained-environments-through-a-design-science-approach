# 📚 Supplementary Materials for the Paper  
**"Educational innovation in resource-constrained environments through a design science approach: HRD class in sLLM-based chatbots"**

This repository provides supplementary materials used in the design and evaluation of an sLLM-based educational chatbot in a Human Resource Development (HRD) classroom setting.

---

## 📁 Repository Structure

```

.
├── chat_data_masked.csv             # Masked chat interaction data for privacy-safe analysis
├── qa_pairs-1_TRANS.jsonl       # QA pairs generated from lecture materials for chatbot training
├── Prompt Engineering.md            # Prompt design principles and constraints used in the study
└── README.md                        # This document

````

---

## 🧾 Descriptions of Each File

### `chat_data_masked.csv`
- Contains privacy-preserved conversation logs between students and the sLLM-based chatbot.
- Fields include:
  - `user_input`: Learner's question or input  
  - `chatbot_response`: Chatbot's reply  
  - `session_id`, `timestamp` for contextual tracking  
- Personally identifiable information (PII) is removed or masked.

### ` qa_pairs-1_TRANS.jsonl`
A structured collection of question-answer pairs extracted and translated from HRD-related lecture materials.

This file served as a core training dataset for fine-tuning the sLLM-based educational chatbot.

It was used to refine and enhance the chatbot’s instructional responses in alignment with HRD learning objectives.

Each JSON object includes:

question: A generated question derived from textbook content

answer: An instructional response aligned with HRD-specific knowledge

### `Prompt Engineering.md`
- Outlines key rules and restrictions applied when prompting the chatbot, including:
  - Contextual constraint to HRD-specific knowledge  
  - No external inference or assumption  
  - Output language restricted to Korean  
  - Guidelines for response fidelity, scope, and clarity

---

## 📌 Purpose of the Repository

These materials support:
- A design science methodology applied to develop LLM-based instructional tools in resource-limited educational contexts.
- Evaluation of chatbot accuracy, reliability, and alignment with human resource development (HRD) learning goals.
- Prompt and data design practices for educational NLP systems.

---

## 📬 Contact

For questions or collaboration inquiries, please contact the corresponding author.
