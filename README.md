# c002-agence-ia — Drovt (drovt.com)

Agence de conseil et d'intégration en intelligence artificielle (C002).
Site statique HTML/CSS vanilla, responsive, sans framework ni base de données.
Déployé via GitHub Pages.

## Structure

```
c002-agence-ia/
  index.html                 — Page d'accueil Drovt
  mentions-legales.html      — Mentions légales Aiybiz
  confidentialite.html       — Politique de confidentialité RGPD
  cgu.html                   — Conditions générales d'utilisation
  css/style.css              — Feuille de styles responsive (thème violet)
  offres/                    — Pages de détail des offres (à créer)
  README.md
```

## Services

- Audit IA
- Conseil stratégique
- Création d'agents IA sur mesure
- Formation aux agents IA
- Accompagnement continu

## Utilisation

1. Déployer via GitHub Pages (activé sur le dépôt)
2. Configurer le domaine `drovt.com` (CNAME vers `atako-startup-studio.github.io`)
3. Créer les pages de détail dans `offres/` (liées depuis l'index)

## Ce qui peut casser

- Les liens vers `offres/*.html` pointent vers des pages non encore créées (404)
- Le lien mail `contact@drovt.com` nécessite la configuration du domaine et MX
- Les pages d'offres individuelles ne sont pas encore créées

## Hébergement

GitHub Pages. Aucune dépendance serveur.
