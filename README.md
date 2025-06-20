# SAT Reading & Writing LLM Evaluation Dataset and Code

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📖 Introduction
A benchmark dataset for evaluating LLMs on SAT-style questions. Contains 90 curated questions with model performance metrics obtained from the College Board SAT Question Bank: satsuitequestionbank.collegeboard.org.

## 🗂️ Dataset Structure
```csv
# Example of code block formatting
Question_ID,Difficulty,Skill_Type,Correct_Answer
eb95235b,hard,boundaries,B

## 🗂️ Google Colab Notebook
# Example notebook utilized for study
# Evaluation code example
from langchain.evaluation import load_evaluator

eval_chain = load_evaluator(
    "labeled_score_string", 
    llm=your_llm_instance
)

MIT License
Copyright (c) 2025 Zixuan Shang

@misc{sat_llm_benchmark2025,
  title={SAT LLM Evaluation Dataset},
  author={Zixuan Shang},
  year={2025},
  url={https://github.com/your/repo}
}
