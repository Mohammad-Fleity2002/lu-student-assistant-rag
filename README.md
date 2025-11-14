# LU Student Assistant RAG – n8n Workflow

This repository contains the full n8n workflow for an AI-powered RAG assistant
used by Lebanese University (LU) students through a Telegram bot.

## Features

- Telegram bot integration
- Retrieval-Augmented Generation (RAG)
- AI agent connected to LU datasets
- English output even if user inputs Arabic
- Option to search the internet if data is not in the LU dataset
- Safety controls for hallucinations
- Markdown formatting
- OCR support for PDFs and images

## Files

- `workflow/LU_Student_Assistant_RAG_Workflow.json`:  
  The full exported n8n workflow.

## Notes

- The model always responds in Arabic.
- If the requested information is not in the LU dataset, the assistant asks:
  _"لا أملك هذه المعلومة في قاعدة بيانات الجامعة اللبنانية. هل ترغب أن أبحث لك على الإنترنت؟"_
