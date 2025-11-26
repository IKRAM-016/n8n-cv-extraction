# 📖 Guide d'Installation

## 1. Prérequis

- Instance n8n fonctionnelle
- Compte Gmail avec accès API
- Compte OpenRouter
- Base Supabase configurée

## 2. Configuration des Credentials n8n

### Gmail OAuth2
1. Aller dans Settings > Credentials
2. Créer un nouveau credential "Gmail OAuth2 API"
3. Suivre le processus d'authentification Google

### OpenRouter
1. Créer un credential "OpenRouter API"
2. Ajouter votre clé API OpenRouter

### Supabase  
1. Créer un credential "Supabase API"
2. Remplir l'URL et la clé de service

## 3. Import du Workflow

1. Dans n8n, aller sur Workflows
2. Cliquer "Import from file"
3. Sélectionner `workflow_cv_extract.json`
4. Vérifier que tous les nodes sont connectés

## 4. Test du Workflow

1. Envoyer un email de test avec CV PDF
2. Vérifier les logs n8n
3. Contrôler les données dans Supabase

## 5. Personnalisation

### Modifier le prompt LLM
Éditer le node "Basic LLM Chain" pour adapter l'extraction

### Changer le modèle
Modifier le node "OpenRouter Chat Model" pour utiliser un autre modèle

### Adapter les tables
Ajuster les noms de tables dans les nodes Supabase