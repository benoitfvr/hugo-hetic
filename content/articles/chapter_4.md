+++
title = '4. Déployer sur Github Pages'
date = 2023-11-17T16:40:20+01:00
draft = false
+++

## Introduction :

GitHub Pages a récemment introduit une fonctionnalité qui rend la publication de blogs Hugo encore plus accessible. Grâce à une option de configuration automatique des GitHub Actions pour des projets Hugo, vous pouvez déployer votre site en quelques clics sans avoir à configurer manuellement vos workflows. Voici les étapes à suivre.

## Étape 1: Préparation de Votre Répertoire Hugo :

Avant de commencer, assurez-vous que votre projet Hugo est prêt et poussé sur un dépôt GitHub. Ce dépôt doit contenir le code source de votre blog, à l'exception du dossier public.

## Étape 2: Activer GitHub Pages:

- Rendez-vous dans les 'Settings' de votre dépôt GitHub.
- Descendez jusqu'à la section 'Pages'.
- Ici, vous pouvez configurer votre source de publication. Habituellement, pour Hugo, vous choisirez la branche gh-pages.

## Étape 3: Configurer les GitHub Actions :

- Toujours dans la section 'Pages', vous verrez maintenant une option pour configurer les GitHub Actions.
- Sélectionnez le framework 'Hugo'. GitHub vous proposera un workflow préconfiguré adapté à Hugo.
- Acceptez et activez ce workflow. GitHub créera automatiquement un fichier de workflow dans un dossier .github/workflows dans votre dépôt.

Si vous avez des exigences spécifiques, comme une version particulière de Hugo ou des étapes de build supplémentaires, vous pouvez modifier le fichier de workflow créé. Cependant, pour la plupart des blogs Hugo standards, la configuration par défaut devrait suffire.

## Étape 4: Publier Votre Site :

Après avoir configuré les Actions, chaque fois que vous pousserez des modifications sur la branche principale (ou la branche que vous avez configurée pour le déploiement), GitHub Actions construira et déploiera automatiquement votre site sur GitHub Pages.
Vérifiez le processus de build dans l'onglet 'Actions' de votre dépôt pour vous assurer que tout se passe comme prévu.

## Conclusion :

Cette fonctionnalité simplifie considérablement le déploiement de blogs Hugo sur GitHub Pages, rendant le processus accessible même pour ceux qui ne sont pas familiers avec les concepts de CI/CD. Avec quelques clics, vous pouvez avoir un blog Hugo fonctionnel et bien présenté, hébergé gratuitement sur GitHub Pages.
