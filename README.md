# chatbot_calendar
A custom AI chatbot that answers user queries from a knowledge base and seamlessly books meetings on Google Calendar. Designed to enhance user interaction and automate scheduling tasks for businesses.

How It Works:
The automation has two main parts:

1. RAG Knowledge Base
The chatbot reads information from a custom knowledge base.
That content is converted into vector embeddings and stored so the chatbot can:
Understand the meaning of the text
Find the most relevant information when a user asks something
Answer questions accurately instead of relying on guesswork
When a query comes in, the system searches the vector store, retrieves the most relevant chunks, and uses them to form a proper response.

2. Calendar Management
Along with answering questions, the chatbot can also handle basic scheduling tasks.
It can:
Create a new event
Update an existing event
Delete an event
Check availability or existing meetings
This makes the chatbot more than just an information bot — it becomes a small assistant that can take action.

Tech Stack:
n8n – main automation workflow
OpenAI / Embedding Model – creating vector embeddings
Vector Store (FAISS / Chroma depending on your workflow)
Google Calendar API – scheduling operations
Custom Knowledge Base (text, notes, docs)

Future Improvements:
Add multi-step conversation memory
Support multiple calendar accounts
Add authentication for user-specific scheduling
Voice-based input/output
Integrate a front-end chat UI



<img width="1819" height="740" alt="Screenshot 2025-11-14 180859" src="https://github.com/user-attachments/assets/06e94588-5f8a-4267-a0bb-72e83a4d6942" />
