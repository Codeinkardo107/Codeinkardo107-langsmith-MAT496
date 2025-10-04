# Langsmith Poject
SUMMARY

By: Bhavya Yadav, 2410110101

---

## Module 1
### 1) tracing_basics.ipynb
Shows how to trace a RAG pipeline(document retrieval + LLM generation) using LangSmith’s @traceable decorator.
The @traceable decorator (from langsmith) can wrap functions to automatically log.
With tracing we can debug issues like unexpected failures or outputs.
- setup, usage, and how to add metadata to traces for better visibility.
- Added some examples.

---
### 2) types_of_run.ipynb
Shows how to trace different types of model and system runs (especially LLMs) using LangSmith’s @traceable.
- setup, input/output formats, metadata, handling streaming responses, and also tool calling.
- Added a LLM run for chat models.

---
### 3) alternative_tracing_methods.ipynb
This notebook shows different ways to trace and debug Python code execution. It demonstrates tracing using the built-in trace module, logging, decorators, context managers, and sys.settrace(). 
Each method shows how to monitor function calls, line execution, and performance. It ends by comparing these techniques, highlighting their pros and cons in terms of simplicity, flexibility, and control.
- Added some examples in every tracing methods
- Added a promt for giving the best tracing methods regarding performance, readability

---
### 4) conversational_threads.ipynb
Thsi notebook explains how to use LangSmith's Threads feature to manage multi-turn conversations for LLM applications like RAG systems. To group traces into a single thread, a unique identifier(UUID) is passed via the langsmith_extra metadata using a key like thread_id, session_id, or conversation_id. The notebook demonstrates this by running a RAG application twice, linking both runs to the same thread_id to show they are part of the same conversation.
- Added a class called conversation manager


---
---

## Module 2
### 1) dataset_upload.ipynb
This notebook demonstrates how to programmatically create and upload datasets to LangSmith using the SDK(Software Development Kit), rather than relying solely on the UI.
<img width="1759" height="912" alt="image" src="https://github.com/user-attachments/assets/9a59ffb5-0dea-426f-90ee-1e5576e7ac64" />
- Changed the question asked in the end cell.

---
### 2) evaluators.ipynb
Demonstrates how to create custom evaluators in LangSmith to automatically score and assess LLM application performance.
Eg. Semantic similarity score: {'score': 1, 'key': 'similarity'}.
- Added a Simple exact match evaluator

---
### 3) experiments.ipynb
Demonstrates how to run systematic experiments in LangSmith to evaluate and compare different versions of LLM applications using datasets and custom evaluators.
Systematic A/B Testing provides a complete framework for comparing different versions of LLM systems using controlled experiments with datasets and custom evaluation metrics.
<img width="1758" height="910" alt="image" src="https://github.com/user-attachments/assets/cb0b681d-0f69-4d4f-b58b-75a0d0c2f7bd" />

 - Added a complete RAG Application with experiment setup
