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

- Audit Flash — Diagnostic rapide de maturité IA (5 jours)
- Package Fondations — Premier cas d'usage IA opérationnel
- Package Essentiel — Intégration structurée multi-agents
- Package Avancé — Transformation IA complète
- Accompagnement — Suivi continu et optimisation
- Ateliers — Formations pratiques pour les équipes

## Utilisation

1. Déployer via GitHub Pages (activé sur le dépôt)
2. Configurer le domaine `drovt.com` (CNAME vers `atako-startup-studio.github.io`)
3. Les pages d'offres sont dans `offres/`, accessibles depuis le landing et entre elles

## Ce qui peut casser

- Le lien mail `contact@drovt.com` nécessite la configuration du domaine et MX
- `js/stripe.js` est référencé mais pas encore créé

## Hébergement

GitHub Pages. Aucune dépendance serveur.
