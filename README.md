# 🤖 Activité Pratique N°1 - Bases du Prompt Engineering

Ce dépôt contient les travaux pratiques réalisés dans le cadre du cours **"IA Agentique"** dirigé par **Mr YOUSSFI Mohamed**. L'objectif est de maîtriser les interactions avec les LLMs (OpenAI, Ollama, Groq) via Python.

---

## 🎯 Objectifs de l'activité
- Configurer un environnement Python avec **UV** (gestionnaire de paquets haute performance).
- Comprendre la **tokenisation** avec la librairie `tiktoken`.
- Interagir avec des LLMs via **LangChain**.
- Expérimenter les techniques de prompting : **Zero-Shot**, **Few-Shot**, **Text-to-Image** et **Vision**.

---

## 📚 Ressources
- 🎥 [Démonstration Vidéo - Bases du Prompt Engineering](https://www.youtube.com/watch?v=2q8TDLN8Drk)
- 🧩 **Backend Logic** : LangChain / Python 3.11+
- 🔧 **Tools** : UV, Ollama (local LLMs), VS Code.

---

## 🧱 Étapes d'installation

### 1️⃣ Initialisation de l'environnement virtuel (UV)
```bash
# Initialiser le projet
uv init
# Créer et activer l'environnement virtuel
uv venv
# Windows
.\.venv\Scripts\activate
# Linux/MacOS
source .venv/bin/activate
```
### 2️⃣ Installation des dépendances
```bash
uv add tiktoken langchain-openai langchain-ollama python-dotenv pillow
```
### 2️⃣ Installation des dépendances
```bash
OPENAI_API_KEY=sk-proj-votre_cle_ici
```
🧠 Concepts Clés & Captures
🔹 1. Tokenisation
Analyse de la transformation du texte en IDs numériques compréhensibles par le modèle.

🔹 2. Zero-Shot vs Few-Shot
Zero-Shot : Demande directe au modèle sans exemples.

Few-Shot : Fournir des exemples (input/output) pour formater la réponse.


## 📸 Captures d'écran – Sécurité et Rôles

---
| Formulaire de Connexion | Formulaire d’Inscription |
|---|---|
| ![](./captures/login-form.png) | ![](./captures/register-form.png) |



🔹 3. Multimodalité (Vision & Image)
Interactions entre le texte et les médias.

Text-to-Image : Génération via OLLAMA.

Image-to-Text : Analyse d'un schéma d'architecture (ex: RAG).


---
| Formulaire de Connexion | Formulaire d’Inscription |
|---|---|
| ![](./captures/login-form.png) | ![](./captures/register-form.png) |


🚀 Exécution du Notebook
Ouvrez le dossier dans VS Code.

Sélectionnez le kernel .venv créé précédemment.

Exécutez le fichier sma.ipynb (ou le fichier correspondant à votre activité).












