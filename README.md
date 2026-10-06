# Fiche USAR PWA

Application PWA interactive pour la fiche technique de détachement USAR.

## Publication GitHub Pages

Le workflow `.github/workflows/deploy-pages.yml` publie automatiquement l'application sur GitHub Pages à chaque push sur `main`.

Après création du dépôt :
1. pousser le contenu de ce dossier sur la branche `main` ;
2. dans GitHub : **Settings → Pages** ;
3. dans **Build and deployment**, sélectionner **GitHub Actions** ;
4. attendre la fin du workflow.

L'application pourra ensuite être installée depuis un smartphone compatible PWA.
