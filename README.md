# Research Assistant - Knowledge Base

Ce projet est une application Streamlit qui sert d'assistant de recherche intelligent, utilisant **ChromaDB** pour gérer une base de connaissances et **Groq AI** pour générer des réponses en fonction des requêtes de l'utilisateur.

## Fonctionnalités

- **Assistant de recherche intelligent** : Répond aux questions des utilisateurs en se basant sur un contexte stocké dans ChromaDB, ou sur les connaissances du modèle Groq AI.
- **Modèles LLM sélectionnables** : Choix entre plusieurs modèles de langage pour générer des réponses (par exemple, `llama3-8b-8192`).
- **Sujets variés** : Possibilité de choisir parmi plusieurs sujets d'intérêt pour explorer des thèmes spécifiques.
- **Interface utilisateur** : Interface simplifiée et conviviale, alimentée par **Streamlit**.

## Technologies utilisées

- **ChromaDB** : Utilisé pour la gestion des embeddings et la requête contextuelle.
- **Streamlit** : Interface utilisateur pour interagir avec l'assistant.
- **Groq AI** : Utilisé pour générer des réponses basées sur des modèles de langage.
- **dotenv** : Chargement sécurisé des variables d'environnement, telles que l'API key de Groq.

## Installation

1. Clonez ce dépôt :

   ```bash
   git clone https://github.com/votre-utilisateur/research-assistant.git
   cd research-assistant
   ```

2. Créez un fichier `.env` à la racine du projet et ajoutez votre API key Groq :

   ```
   GROQ_API_KEY=your_groq_api_key
   ```

3. Installez les dépendances :

   ```bash
   pip install -r requirements.txt
   ```

4. Lancez l'application Streamlit :

   ```bash
   streamlit run app.py
   ```

## Dépendances

Les principales dépendances sont listées dans le fichier `requirements.txt` :

```
streamlit==1.26.0
chromadb==0.3.22
python-dotenv==1.0.0
phidata
```

Installez-les via `pip` en utilisant la commande :

```bash
pip install -r requirements.txt
```

## Usage

Une fois l'application lancée, vous pouvez interagir avec l'assistant de recherche via l'interface Streamlit. Sélectionnez un modèle et un sujet d'intérêt, puis posez des questions à l'assistant.
