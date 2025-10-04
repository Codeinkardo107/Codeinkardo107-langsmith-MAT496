# Langsmith Poject
SUMMARY

By: Bhavya Yadav, 2410110101

---

## Module 1
### tracing_basics.ipynb
Shows how to trace a RAG pipeline(document retrieval + LLM generation) using LangSmith’s @traceable decorator.
The @traceable decorator (from langsmith) can wrap functions to automatically log.
With tracing we can debug issues like unexpected failures or outputs.
- setup, usage, and how to add metadata to traces for better visibility.
- Added some examples.

### types_of_run.ipynb
Shows how to trace different types of model and system runs (especially LLMs) using LangSmith’s @traceable.

- setup, input/output formats, metadata, handling streaming responses, and also tool calling.
- Added a LLM run for chat models.
