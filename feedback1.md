- **Feedback 1**
    
    Hello Apprenant1 🙂!
    
     Suite à une analyse approfondie de ton parcours sur le projet Triple Triad Deck Builder, voici mes observations et suggestions :
    
    ### **1. Fichier : index.js**
    
    - **Organisation du code** :
        - Assure-toi que l'importation de `dotenv` et son initialisation soient placées avant l'importation d'`express` pour une meilleure lisibilité.
    - **Chemin des vues et des fichiers statiques** :
        - Privilégie les chemins sans le `./` initial pour une meilleure clarté, par exemple, utilise `app/views` au lieu de `./app/views`.
    - **Configuration de la session** :
        - Pense à inclure des options supplémentaires pour la session comme `resave: true` et `saveUninitialized: true`.
    - **Middleware pour initialiser le deck** :
        - Considère l'ajout d'un middleware pour initialiser le deck dans la session afin de garantir sa disponibilité constante.

    
    ### **2. Fichier : database.js**
    
    - **Structure du code** :
        - Bon travail sur l'importation et l'initialisation du client avec l'URL de la base de données.
    
    ### **3. Routers et Controllers** :
    
    - **Middleware `cardSession`** :
        - Analyse l'utilité de ce middleware et sa mise en œuvre correcte.
    - **Routes** :
        - Bien joué pour l'ajout d'une gestion des erreurs 404. Assure-toi que cette gestion n'interfère pas avec d'autres routes.
    - **Controllers** :
        - Veille à ce que le nom de tes fichiers et méthodes reflète clairement leur fonctionnalité.
        - Dans l'ajout de cartes à un deck, n'oublie pas de vérifier l'existence de la carte avant son ajout.
    - **Gestion des erreurs** :
        - Envisage d'afficher une page d'erreur plutôt qu'un simple message texte.
    - **Recherche par élément** :
        - Poursuis ton travail en suivant l'approche proposée dans la version de correction pour gérer la recherche par élément.
    
    ### **4. DataMapper** :
    
    - **Gestion des éléments nuls** :
        - Évite d'avoir des méthodes inutilisées ou redondantes. Par exemple, `searchByElementNull` semble inutilisé.
    - **Requête SQL pour la recherche par valeur** :
        - Suis l'approche de la version de correction pour formuler des requêtes SQL robustes.
    
    ---
    
    **Feedback général** :
    Ton travail montre une solide compréhension des concepts abordés dans cet atelier. Cependant, il y a des points à améliorer, notamment en matière d'organisation du code, de gestion des erreurs, et de suivis des meilleures pratiques de codage. Supprime également le code commenté pour une meilleure lisibilité.
    
    Je t'encourage à revisiter la version de correction pour t'assurer de bien comprendre chaque étape et chaque décision de conception. N'hésite pas à poser des questions ou à chercher des clarifications si certaines parties restent floues.
    
    Continue comme ça, et bon courage pour la suite de ta formation !🚀🚀 🚀 