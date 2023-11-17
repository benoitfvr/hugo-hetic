+++
title = '3. Publier son projet sur Github Pages'
date = 2023-11-16T16:40:20+01:00
draft = false
+++

# Étape 1: Configuration de GitHub

Si vous n'avez pas de compte GitHub, créez-en un sur GitHub. Ensuite, créez un nouveau dépôt. Le nom de ce dépôt doit être votre_nom_utilisateur.github.io.

# Étape 2: Publication sur GitHub Pages

Pour publier votre site, vous devez d'abord générer les fichiers statiques. Dans votre terminal, naviguez vers le dossier de votre site et exécutez :

```
hugo
```

Cela générera un dossier public contenant votre site. Vous devez maintenant pousser ce dossier sur GitHub.

```
cd public
git init
git remote add origin https://github.com/votre_nom_utilisateur/votre_nom_utilisateur.github.io.git
git add .
git commit -m "Premier déploiement"
git push -u origin master
```

# Conclusion

Félicitations, votre blog est maintenant en ligne sur https://votre_nom_utilisateur.github.io! Hugo combiné à GitHub Pages offre une solution simple et efficace pour lancer un blog. Bonne écriture et publication !
