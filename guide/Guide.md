# 📖 Installation Guide

## 1. Prerequisites

- Working n8n instance
- Gmail account with API access  
- OpenRouter account
- Configured Supabase database

## 2. n8n Credentials Configuration

### Gmail OAuth2
1. Go to Settings > Credentials
2. Create a new "Gmail OAuth2 API" credential
3. Follow Google authentication process

### OpenRouter
1. Create an "OpenRouter API" credential  
2. Add your OpenRouter API key

### Supabase
1. Create a "Supabase API" credential
2. Fill in service URL and key

## 3. Workflow Import

1. In n8n, go to Workflows
2. Click "Import from file"
3. Select `workflow_cv_extract.json`
4. Verify all nodes are connected

## 4. Workflow Testing

1. Send a test email with PDF CV
2. Check n8n logs
3. Verify data in Supabase

## 5. Customization

### Modify LLM Prompt
Edit the "Basic LLM Chain" node to adapt extraction

### Change Model
Modify the "OpenRouter Chat Model" node to use another model

### Adjust Tables
Update table names in Supabase nodes
