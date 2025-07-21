# AI-Powered-Email-Responder-n8n

This project automates customer email responses using an AI agent that understands and applies company policies stored in a vector-based knowledge database. It consists of two integrated workflows.
1.	Workflow 1 handles document ingestion, converting files (PDF, DOCX, etc.) into vector embeddings using Pinecone to update the knowledge base.
2.	Workflow 2 listens for incoming emails, sends the content to an AI agent, and generates replies based on the processed knowledge.
The system ensures accurate, context-aware, and policy-compliant replies to customer queries via email.

# 🛠 Tools & Technologies Used:

Tool / Service	
n8n	- Workflow automation platform to manage triggers and actions
IMAP (Gmail/Microsoft) - Email trigger source for incoming messages
SMTP (Gmail/Microsoft) - Used to send AI-generated email replies to customers
Pinecone - Vector database to store and query embedded knowledge from documents
AI Agent (Chat Model)- Handles language understanding and generates context-aware responses
Cloud Storage (GDrive, S3, etc.) - Stores source documents that feed the knowledge base
