# 🧪 EduCertify — Évaluateur Pédagogique Expert

[![Skill](https://img.shields.io/badge/hermes-skill-purple)](https://hermes-agent.nousresearch.com)
[![Category](https://img.shields.io/badge/category-research-blue)]()

> **EduCertify** est un système d'évaluation pédagogique multidimensionnel pour contenus éducatifs destinés aux enfants (0-12 ans). Combine neurosciences cognitives, psychologie du développement, philosophie de l'éducation et critique littéraire spécialisée jeunesse.

---

## 🔬 Pourquoi EduCertify ?

Le marché de l'éducation enfantine est saturé de contenus "pédagogiques" qui ne sont ni testés, ni structurés, ni réellement adaptés au développement cognitif des enfants. EduCertify apporte une **rigueur de certification** là où il n'existe que des promesses marketing.

**Un verdict clair sur 5 niveaux :**
- ✅ Certification recommandée
- 🟡 Certification conditionnelle
- 🟠 Refus avec potentiel
- 🔴 Refus
- ⛔ Refus catégorique

---

## 📐 Méthodologie — 8 Dimensions d'Analyse

| # | Dimension | Fondement | Poids |
|---|---|---|------|
| 1 | **Alignement développemental** | Piaget, Vygotsky | x1.5 |
| 2 | **Charge cognitive** | Sweller, neurosciences | x1.5 |
| 3 | **Objectifs pédagogiques** | Taxonomie de Bloom | x1.5 |
| 4 | **Mémorisation et ancrage** | Neuro-éducation | x1 |
| 5 | **Engagement et motivation** | Deci & Ryan, Csikszentmihalyi | x1 |
| 6 | **Éthique et sous-entendus** | Analyse critique | x1.5 |
| 7 | **Qualité de la forme** | Design pédagogique | x1 |
| 8 | **Impact transformatif** | Mesure d'impact réel | x1 |

**Score total pondéré sur 100 points.**

---

## 🎯 Quand utiliser EduCertify ?

Ce skill est conçu pour les **créateurs de contenu éducatif**, les **éditeurs jeunesse**, les **enseignants**, les **parents exigeants** et les **investisseurs EdTech** qui veulent savoir si un produit éducatif tient vraiment ses promesses.

Types de contenu évaluables :
- 📚 Livres illustrés et albums jeunesse
- 📖 Manuels scolaires
- 🎲 Jeux de société éducatifs
- 📱 Applications et jeux vidéo
- 🎥 Vidéos et contenus numériques
- 🧰 Kits d'activités et ateliers
- 🎧 Podcasts éducatifs

---

## ⚡ Utilisation

### Dans Hermes Agent

Charge le skill :
```
skill_view(name='educertify')
```

Puis fournis ton contenu éducatif avec le contexte nécessaire (type, âge cible, objectifs). L'analyse complète est générée automatiquement.

### Exemple de prompt

> "J'ai un livre illustré pour les 3-6 ans sur les émotions. Voici le texte intégral et la description des illustrations... EduCertify, analyse."

---

## 🧠 Principes Fondamentaux

1. **Honnêteté implacable** — Un contenu médiocre reçoit un verdict médiocre, avec des axes d'amélioration concrets
2. **Distinction intention/réalité** — Ce que le créateur *voulait faire* ≠ ce que le contenu *produit réellement*
3. **Neutralité absolue** — La beauté de la forme, le coût de production, la réputation de l'auteur n'influencent pas le verdict
4. **Bienveillance constructive** — Chaque critique est accompagnée d'une piste d'amélioration actionnable
5. **Transparence des limites** — Ce qui n'a pas pu être évalué est explicitement signalé

---

## 📊 Exemple de Verdict

```
| Dimension | Score /10 | Coeff | Pondéré |
|---|---|---|---|
| 1. Alignement développemental | 8 | x1.5 | 12 |
| 2. Charge cognitive | 9 | x1.5 | 13.5 |
| 3. Objectifs / Bloom | 7 | x1.5 | 10.5 |
| 4. Mémorisation | 6 | x1 | 6 |
| 5. Engagement | 8 | x1 | 8 |
| 6. Éthique | 9 | x1.5 | 13.5 |
| 7. Qualité forme | 8 | x1 | 8 |
| 8. Impact transformatif | 5 | x1 | 5 |
| **TOTAL** | | | **76.5/100** |

🟡 **CERTIFICATION CONDITIONNELLE** — Contenu solide, améliorations ciblées avant certification.
```

---

## 🏗️ Architecture

```
educertify/
├── SKILL.md          # Grille d'évaluation complète (8 dimensions, scoring, verdict)
├── README.md         # Bio du projet
└── (références/)     # Templates, exemples, guides (à venir)
```

---

## 🤝 Contribution

Ce skill est un cadre vivant. Les améliorations possibles :
- Ajout de références à des études de cas réelles
- Templates de rapport automatisés
- Création d'une base de benchmarks pour la calibration des scores

---

## 📜 Licence

Usage libre dans le cadre du projet **Le Labo du Futur** et des créations associées.

---

*"L'enfant n'est pas un vase qu'on remplit, mais un feu qu'on allume." — Adapté de Montaigne, via EduCertify.*
