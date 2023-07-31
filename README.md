# ChatwithMultiplePDF

-------------------COMMENT CA MARCHE--------------------

  L'application suit les étapes suivantes pour répondre à vos questions :

Chargement du PDF : L'application lit plusieurs documents PDF et en extrait le contenu textuel.

Découpage du texte : Le texte extrait est divisé en morceaux plus petits qui peuvent être traités efficacement.

Modèle linguistique : L'application utilise un modèle linguistique pour générer des représentations vectorielles (embeddings) des morceaux de texte.

Correspondance des similitudes : lorsque vous posez une question, l'application la compare aux morceaux de texte et identifie ceux qui sont les plus similaires sur le plan sémantique.

Génération de réponses : Les morceaux sélectionnés sont transmis au modèle linguistique, qui génère une réponse basée sur le contenu pertinent des PDF.


--------------------INSTALLATION DES DEPENDANCES--------------------

Pour installer l'application MultiPDF Chat, veuillez suivre les étapes suivantes :

Clonez le dépôt sur votre machine locale.

Installez les dépendances requises en exécutant la commande suivante :

pip install -r requirements.txt

Obtenez une clé API auprès d'OpenAI et ajoutez-la au fichier .env dans le répertoire du projet.

OPENAI_API_KEY=votre_clé_api_secret


-------------------COMMENT UTILISER-------------------

Pour utiliser l'application MultiPDF Chat, suivez les étapes suivantes :

Assurez-vous que vous avez installé les dépendances requises et ajouté la clé API OpenAI au fichier .env.

Exécutez le fichier main.py à l'aide de la CLI Streamlit. Exécutez la commande suivante :

streamlit run app.py

L'application se lancera dans votre navigateur web par défaut et affichera l'interface utilisateur.

Chargez plusieurs documents PDF dans l'application en suivant les instructions fournies.

Posez des questions en langage naturel sur les PDF chargés à l'aide de l'interface de discussion.
