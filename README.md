# BS Linktree

L'objectif de ce projet est d'offrir une alternative gratuite aux services comme Linktree, permettant de centraliser tous les liens vers mes différents réseaux sociaux et plateformes en ligne. Ce projet est pensé pour être léger, rapide et personnalisable.


📸 Comment cloner le projet ?

Ce projet est basé sur le template original Astrolink de @alamguardin. Je vous conseille donc de repartir de sont Template.

```
git clone https://github.com/alamguardin/Astrolink.git
```

🚀 Comment modifier le contenu ?

Pour personnaliser le template, il suffit de modifier le fichier user.json situé dans le dossier data. Vous pouvez y configurer votre nom, votre profession et vos liens personnalisés.

De plus, vous avez accès à toute l’iconographie de Remixicons. Il suffit d’indiquer le nom de l’icône dans la clé "icon" de chaque lien dans le fichier user.json.




## 🧞 Commandes

Toutes les commandes sont à exécuter depuis la racine du projet dans un terminal :


| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| npm install             | Installs dependencies                            |
| npm run dev             | Starts local dev server at localhost:4321      |
| npm run build           | Build your production site to ./dist/          |
| npm run preview         | Preview your build locally, before deploying     |
| npm run astro ...       | Run CLI commands like astro add, astro check |
| npm run astro -- --help | Get help using the Astro CLI                     |