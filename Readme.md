# TD  : Stylisation Avancée avec CSS

## Objectifs pédagogiques

Ce travail  vous permettra de :
- **Analyser** la structure HTML existante et identifier les éléments à styliser
- **Comparer** un rendu incomplet avec le résultat attendu
- **Appliquer** des propriétés CSS avancées (pseudo-classes, positionnement, effets visuels, pseudo-éléments, etc.)
- **Développer** votre autonomie dans la résolution de problèmes CSS
- **Maîtriser** l'utilisation des outils de développement du navigateur

## Contexte de l'exercice

Vous disposez d'un site web fonctionnel avec deux pages :
- **Page d'accueil** (`index.html`) - Stylisée par `main.css` (incomplet)
- **Page blog** (`blog.html`) - Stylisée par `blog.css` (incomplet)

**Votre mission :** Compléter les fichiers `style-main.css` et `style-blog.css` pour obtenir le rendu final souhaité.

**Important :** Vous ne devez **jamais modifier** les fichiers HTML ni les fichiers CSS de base (`main.css` et `blog.css`). Travaillez exclusivement dans les fichiers `style-main.css` et `style-blog.css`.

## Rendu attendu

Consultez le rendu final à atteindre : [Voir le résultat attendu](https://td-boite.vercel.app/index.html)

## Configuration initiale

### Prérequis
- Éditeur de code (VS Code recommandé)
- Terminal intégré ou Git Bash (Windows)
- Navigateur web moderne avec outils de développement

### Installation

**NB** Si vous êtes sur **Windows**, utilisez Git Bash pour exécuter les commandes suivantes. si vous êtes sur **macOS**, utilisez le terminal natif.

```bash
# 1. Cloner le projet
git clone https://github.com/votre-utilisateur/votre-repo.git

# 2. Nettoyer la configuration Git (important !)
git remote remove origin

# 3. Supprimer le dossier .git pour éviter les conflits
rm -rf .git


```

## Méthodologie de travail

### Étape 1 : Analyse et observation
1. **Examinez attentivement** la structure HTML des deux pages (index.html et blog.html)
2. **Identifiez** les éléments présents et leur hiérarchie
3. **Comparez** l'état actuel avec le rendu final attendu


### Étape 2 : Planification
1. **Priorisez** les modifications par ordre de complexité
2. **Identifiez** les propriétés CSS nécessaires pour chaque section
3. **Organisez** votre travail section par section

### Étape 3 : Développement
1. **Travaillez progressivement** : une section à la fois
2. **Testez fréquemment** vos modifications dans le navigateur
3. **Utilisez l'inspecteur** pour expérimenter avant d'écrire le CSS définitif
4. **Documentez et indentez** votre code avec des commentaires clairs


## Conseils techniques

### Utilisation de l'inspecteur
- **F12** ou **Ctrl+Shift+I** pour ouvrir les outils de développement
- **Onglet Elements** : modifier le CSS en temps réel


### Bonnes pratiques CSS
- **Commentez** vos sections pour une meilleure lisibilité
- **Groupez** les propriétés logiquement
- **Évitez** la duplication de code(DRY - Don't Repeat Yourself)



## Livrables attendus

- [ ] Fichier `style-main.css` complété
- [ ] Fichier `style-blog.css` complété  
- [ ] Rendu visuel conforme aux attentes
- [ ] Code CSS propre et documenté
- [ ] Site fonctionnel et déployé en ligne et lien du repo GitHub ou GitLab


**Options recommandées :**
- **Vercel** : [vercel.com](https://vercel.com)
- **Netlify** : [netlify.com](https://netlify.com)
- **GitHub Pages** : [pages.github.com](https://pages.github.com)

## Ressources utiles

- [Documentation MDN CSS](https://developer.mozilla.org/fr/docs/Web/CSS)

---

**Bon courage !** N'hésitez pas à expérimenter et à poser des questions si vous rencontrez des difficultés.