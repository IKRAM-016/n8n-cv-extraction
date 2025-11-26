# 🧠 CV Extraction – n8n Automation

Automatic system for extracting and analyzing CVs via email using n8n and AI.

## 🚀 Features

- 📧 **Email Trigger**: Automatic monitoring of the Gmail inbox
- 📄 **PDF Extraction**: Analysis of CVs received as attachments  
- 🤖 **AI Analysis**: Structured information extraction using an LLM
- 💾 **Supabase Storage**: Saves results into a database
- 🔄 **Automated Workflow**: Real-time processing

## 🛠️ Technologies

- **n8n** – Workflow orchestration
- **OpenRouter** – Language models (Mistral 7B)
- **Supabase** – Database storage
- **Gmail API** – Email reception

## ⚡ Quick Installation

1. Import the workflow into n8n
2. Configure the credentials (see `config-example.json`)
3. Start the workflow

## 📋 Required Configuration

- n8n account (self-hosted or cloud)
- OpenRouter API key  
- Supabase account
- Gmail API access

## 🔧 Usage

When an email with an attached CV is received, the workflow automatically triggers.

The extracted information includes:
- 📝 **Personal details** (name, email, phone)
- 🎓 **Education and academic background**
- 💼 **Professional experience** 
- 🛠️ **Technical skills**

---

*For detailed setup instructions, see [guide/Guide.md](guide/Guide.md)*
