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

### 2) types_of_run.ipynb
Shows how to trace different types of model and system runs (especially LLMs) using LangSmith’s @traceable.
- setup, input/output formats, metadata, handling streaming responses, and also tool calling.
- Added a LLM run for chat models.


### 3) alternative_tracing_methods.ipynb
This notebook shows different ways to trace and debug Python code execution. It demonstrates tracing using the built-in trace module, logging, decorators, context managers, and sys.settrace(). 
Each method shows how to monitor function calls, line execution, and performance. It ends by comparing these techniques, highlighting their pros and cons in terms of simplicity, flexibility, and control.
- Added some examples in every tracing methods
- Added a promt for giving the best tracing methods regarding performance, readability


### 4) conversational_threads.ipynb
