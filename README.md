# 📊 Projet MEAFGP — Gestion de Portefeuille Financier

**Université Sorbonne Paris Nord — Master 1 MBFA**
**Module : Méthodes et Applications en Finance et Gestion de Portefeuille**
**Année académique : 2025–2026**

---

## 🎯 Objectif du projet

Ce projet consiste à construire et analyser un **portefeuille optimisé** composé de **10 actions britanniques du FTSE 100**, sur la période **2013–2022**, en appliquant les modèles classiques de la théorie moderne du portefeuille.

Un suivi de performance sur le **mois de mars 2026** vient compléter l'analyse historique.

---

## 📁 Contenu du dépôt

| Fichier | Description |
|---|---|
| `Projet_MEAFGP_CORRIGE.xlsx` | Fichier Excel complet : données, statistiques, Markowitz, Sharpe, performances |
| `Rapport_MEAFGP_V2_FINAL.pdf` | Rapport académique complet (16 pages) |
| `Presentation_MEAFGP_2026.pptx` | Présentation PowerPoint (13 diapositives) |

---

## 📈 Les 10 actions étudiées

| Ticker | Entreprise | Secteur |
|---|---|---|
| SHEL | Shell | Énergie (pétrole & gaz) |
| GSK | GlaxoSmithKline | Santé & Pharmacie |
| DGE | Diageo | Boissons & Alcools |
| GLEN | Glencore | Matières premières |
| NWG | NatWest Group | Banque & Finance |
| AZN | AstraZeneca | Pharmacie & Biotech |
| BATS | British American Tobacco | Tabac |
| RTO | Rentokil Initial | Services aux entreprises |
| NG | National Grid | Énergie (utilities) |
| LSEG | London Stock Exchange Group | Services financiers |

---

## 🔬 Méthodologie

### 1. Statistiques descriptives
- Rendements journaliers, annualisés
- Volatilité, asymétrie, kurtosis
- Matrice de corrélation

### 2. Modèle de Markowitz
- Construction de la **frontière efficiente**
- Identification du **portefeuille à variance minimale (PMin)**
- Calcul via l'optimisation Lagrangienne : `w* = λΩ⁻¹1 + γΩ⁻¹μ`

### 3. Modèle de Sharpe (modèle de marché)
- Régression de chaque action sur le FTSE 100
- Estimation des **bêtas** (risque systématique) et **alphas**
- Rapport ToolPak complet (ANOVA, IC 95%)

### 4. Sélection par la méthode Elton-Gruber (C*)
- Classement par **ratio de Treynor**
- Calcul du seuil optimal **C* = 0,054**
- Portefeuille retenu : **RTO (85,13%)** + **DGE (14,87%)**

### 5. Analyse des performances historiques
- NAV base 100 sur 2013–2022
- Rendement annualisé, volatilité, **ratio de Sharpe**
- Drawdown maximum

### 6. Suivi mars 2026
- Comparaison hebdomadaire : FTSE 100 vs PMin vs Portefeuille Sharpe Optimal
- Résultat : FTSE **-5,95%** | PMin **-2,87%** | Sharpe Opt. **-3,40%**

---

## 📊 Résultats clés

> Le portefeuille à variance minimale (PMin) a surperformé le marché en période de stress :
> **-2,87%** contre **-5,95%** pour le FTSE 100 en mars 2026.

| Portefeuille | Rendement mars 2026 | Volatilité historique |
|---|---|---|
| FTSE 100 | -5,95% | — |
| PMin (Markowitz) | **-2,87%** | Minimale |
| Sharpe Optimal (Elton-Gruber) | -3,40% | Modérée |

---

## 🛠️ Outils utilisés

- **Microsoft Excel** (Solver, Analyse ToolPak, régressions)
- **Python** (pandas, numpy, matplotlib, scipy)
- **LaTeX** (rédaction du rapport académique)
- **PowerPoint** (présentation orale)

---

## 👤 Auteur

**TRAORE**
Master 1 MBFA — Université Sorbonne Paris Nord
Contact : tsory728@gmail.com

---

*Projet réalisé dans le cadre du cours de Gestion de Portefeuille — 2025/2026*
