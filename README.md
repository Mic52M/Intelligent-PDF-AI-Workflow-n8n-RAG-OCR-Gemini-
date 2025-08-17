# Intelligent PDF AI Workflow - n8n RAG OCR Gemini

A hands-on n8n workflow that automates PDF document processing using OCR, text chunking, vector embeddings, and AI-powered question answering. This project demonstrates a practical RAG (Retrieval Augmented Generation) pipeline built for learning and experimentation with modern AI document processing techniques.

Built as a personal learning project to explore the integration of OCR technology, vector databases, and large language models in a unified automation workflow. The system takes PDF documents, extracts text through OCR, creates searchable embeddings, and enables intelligent querying using Gemini or OpenAI models.

## How It Works

The workflow follows a simple but powerful pipeline:

1. **PDF Input** → Upload or drop PDF documents into the system
2. **OCR Processing** → Extract text content from images and scanned documents
3. **Text Chunking** → Break down content into manageable, overlapping segments
4. **Embedding Creation** → Generate vector representations of text chunks
5. **Vector Storage** → Store embeddings in Qdrant vector database
6. **AI Question-Answering** → Query documents using Gemini or OpenAI with RAG logic

## Features

- **Full Automation**: End-to-end PDF processing without manual intervention
- **AI Pipeline Integration**: Seamless connection between OCR, embeddings, and LLM
- **Hands-on n8n Orchestration**: Visual workflow management and monitoring
- **RAG Logic Implementation**: Retrieval-augmented generation for accurate responses
- **Flexible AI Models**: Support for both Gemini and OpenAI language models
- **Vector Search**: Efficient document querying through Qdrant vector database

## Getting Started

1. Import the workflow JSON file into your n8n instance
2. Configure your API keys for:
   - Gemini or OpenAI (for language model)
   - Qdrant (for vector database)
   - OCR service credentials
3. Set up your document input method (webhook, file monitor, etc.)
4. Test with sample PDF documents
5. Start querying your processed documents!

Detailed configuration steps and environment setup instructions are included in the workflow documentation.

## Screenshots & Examples

*Coming soon - workflow screenshots and example queries will be added here*

## Questions or Demo?

Interested in seeing this workflow in action or need help setting it up? Feel free to reach out! I'm happy to provide a detailed walkthrough or assist with configuration and customization for your specific use case.

---

*This project represents a practical exploration of modern AI document processing techniques using n8n's visual workflow capabilities.*
