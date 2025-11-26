# 🧠 CV Extraction - Automatisation n8n

Système automatique d'extraction et d'analyse de CV via email utilisant n8n et IA.

## 🚀 Fonctionnalités

- 📧 **Déclenchement par email** : Surveillance automatique de la boîte Gmail
- 📄 **Extraction PDF** : Analyse des CV reçus en pièces jointes
- 🤖 **Analyse IA** : Extraction structurée des informations avec LLM
- 💾 **Stockage Supabase** : Sauvegarde dans une base de données
- 🔄 **Workflow automatisé** : Traitement en temps réel

## 🛠️ Technologies

- **n8n** : Orchestration du workflow
- **OpenRouter** : Modèles de langage (Mistral 7B)
- **Supabase** : Base de données
- **Gmail API** : Réception des emails

## ⚡ Installation Rapide

1. **Importer le workflow** dans n8n
2. **Configurer les credentials** (voir `config-example.json`)
3. **Démarrer le workflow**

## 📋 Configuration Requise

- Compte n8n (self-hosted ou cloud)
- Clé API OpenRouter
- Compte Supabase
- Accès Gmail API

## 🔧 Utilisation

Le workflow s'active automatiquement à la réception d'un email avec un CV en pièce jointe. Les données extraites sont :
- 📝 Informations personnelles (nom, email, téléphone)
- 🎓 Formation et éducation
- 💼 Expériences professionnelles  
- 🛠️ Compétences techniques

---

*Pour la configuration détaillée, voir [guide/Guide.md](guide/Guide.md)*
