
### C'est quoi un MCD ? 🎨

Imagine un MCD comme un grand puzzle. Chaque pièce a une place précise et certaines pièces peuvent être connectées à plusieurs autres. Les pièces sont vos données et la manière dont elles s'emboîtent, c'est ce qu'on appelle les "cardinalités". 🧩

### Les pièces de notre puzzle :

1. **Utilisateur** 🙋‍♂️: C'est toi, ou n'importe qui utilisant l'app.
   - Et bien sûr, pour te connaître un peu mieux, on a ton nom, prénom, et email.
   
2. **Adresse** 🏡: C'est l'endroit où tu veux recevoir tes mugs trop cool.
   - Tu pourrais avoir plusieurs adresses (peut-être une à la maison, une au travail).
   
3. **Mug O'Clock** ☕: C'est la star de notre site ! 
   - Il a un nom, une histoire et un prix.
   
4. **Commande** 🛍️: C'est quand tu trouves un mug tellement génial que tu décides de l'acheter.
   
5. **Like** ❤️: C'est quand un mug te fait de l'œil et que tu veux lui montrer un peu d'amour.

### Comment les pièces s'assemblent (cardinalités) :

- **Possède** 🚪: Un utilisateur peut "posséder" plusieurs adresses. Mais chaque adresse appartient à un seul utilisateur. (1 utilisateur pour plusieurs adresses)
- **Like** 💖: Un utilisateur peut "liker" plusieurs mugs et un mug peut être "liké" par plusieurs utilisateurs. C'est un peu comme un club de fans où chaque fan aime plusieurs stars, et chaque star a plusieurs fans. (Plusieurs utilisateurs pour plusieurs mugs)
- **Commande** 🎁: Un utilisateur peut commander plusieurs mugs, mais chaque commande est unique à un utilisateur et un mug. (1 utilisateur pour 1 mug)

### Outils pour créer ton puzzle (MCD) :

- **Lucidchart** 📊: C'est un outil en ligne super intuitif pour dessiner ton MCD. Il a des tonnes de formes et de modèles pour t'aider à démarrer.
- **MySQL Workbench** 💼: C'est un outil plus technique qui te permet non seulement de dessiner ton MCD, mais aussi de le convertir directement en une base de données.
- **Draw.io** ✏️: C'est un autre outil en ligne pour créer des diagrammes. Il est simple, gratuit, et ne nécessite pas d'installation.

Voilà, avec ces explications et outils, tu es prêt à assembler ton puzzle MCD et à donner vie à ton application ! 🎉🚀🌟

