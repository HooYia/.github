<div align="center">

# HooYia

### No Limit In Mind — Digital Engineering

[![Website](https://img.shields.io/badge/website-hooyia.net-F5821F?style=flat-square)](https://hooyia.net)
[![Flagship](https://img.shields.io/badge/flagship-Hoolearn-0E1E3D?style=flat-square)](https://hoolearn.net)

</div>

---

## 👋 À propos

HooYia est un studio d'ingénierie logicielle basé au Cameroun. Nous
concevons et opérons des plateformes SaaS, des outils IA/ML et des
marketplaces numériques — de la première ligne de code jusqu'à
l'infrastructure qui les fait tourner en production.

## 🚀 Projet phare : Hoolearn

**[Hoolearn](https://hoolearn.net)** est notre plateforme e-learning en
production, avec paiements réels (Stripe, PayPal, Flutterwave) et une
infrastructure AWS entièrement pilotée par Terraform.

| Dépôt | Rôle |
|---|---|
| [`elearning-hooyia`](https://github.com/HooYia/elearning-hooyia) | Application Django |
| [`elearning-infrastructure`](https://github.com/HooYia/elearning-infrastructure) | Infrastructure AWS (Terraform) |

## 🛠️ Comment on travaille

Nos dépôts actifs suivent un même standard, pas juste des bonnes
intentions :

- **Revue obligatoire** — aucune fusion sur `main` sans 2 approbations de
  l'équipe technique (`CODEOWNERS` + règles de branche)
- **CI complète** — lint, types, tests, et scan de sécurité (SAST,
  dépendances, secrets, image conteneur, IaC) sur chaque Pull Request ;
  toute faille détectée ouvre une issue et bloque la fusion
- **Déploiement traçable** — versions sémantiques automatiques, chaque
  déploiement et rollback est un geste explicite et journalisé, jamais
  une surprise
- **Infrastructure as Code** — tout changement d'infrastructure passe
  par un plan Terraform relu avant d'être appliqué

## 👥 Équipe

| Équipe | Rôle |
|---|---|
| `tech-leads` | Revue et approbation des Pull Requests |
| `devbackend` | Développement backend et architecture |
| `devfrontend` | Développement frontend |
| `internproject` | Stagiaires et projets d'apprentissage |

## 💻 Stack principale

Python · Django · Terraform · AWS · GitHub Actions · PostgreSQL

---

<div align="center">

*Merci de votre visite — on construit ça sérieusement.*

</div>
