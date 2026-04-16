# 📊 Projet MEAFGP — Gestion de Portefeuille Financier

**Université Sorbonne Paris Nord — Master 1 MBFA**
**Module : Méthodes et Applications en Finance et Gestion de Portefeuille**
**Année académique : 2025–2026 | Auteur : TRAORE**

---

## 🎯 Objectif du projet

Construction et analyse d'un **portefeuille optimisé** composé de **10 actions britanniques du FTSE 100**, sur la période **2013–2022**, en appliquant les modèles classiques de la théorie moderne du portefeuille (Markowitz, Sharpe, Elton-Gruber). Un suivi de performance sur **mars 2026** complète l'analyse.

---

## 📁 Fichiers du dépôt

| Fichier | Description |
|---|---|
| `Projet_MEAFGP.xlsx` | Données, statistiques, Markowitz, Sharpe, performances |
| `Rapport_MEAFGP_V2_FINAL.pdf` | Rapport académique complet (16 pages) |
| `Presentation_MEAFGP_2026.pptx` | Présentation PowerPoint (13 diapositives) |
| `Descriptif_Projet_MEAFGP.docx` | Descriptif du projet |

---

## 📈 Les 10 actions étudiées (FTSE 100)

| Ticker | Entreprise | Secteur |
|---|---|---|
| NWG | NatWest Group | Banque & Finance |
| PHNX | Phoenix Group | Assurance |
| DGE | Diageo | Boissons & Alcools |
| ABF | Associated British Foods | Agroalimentaire |
| IMB | Imperial Brands | Tabac |
| RR | Rolls-Royce Holdings | Aérospatiale |
| RTO | Rentokil Initial | Services aux entreprises |
| GLEN | Glencore | Matières premières |
| BDEV | Barratt Developments | Immobilier |
| KGF | Kingfisher | Distribution |

---

## 🔬 Méthodologie

Le projet repose sur quatre étapes :

1. **Statistiques descriptives** — rendements, volatilité, corrélations
2. **Modèle de Markowitz** — frontière efficiente, portefeuille à variance minimale (PMin)
3. **Modèle de Sharpe** — régression sur FTSE 100, bêtas et alphas
4. **Méthode Elton-Gruber (C\*)** — sélection optimale par ratio de Treynor

---

## 📊 Graphiques

### 1. Taux sans risque — UK Gilt 10 ans
![Taux sans risque](fig1_rf.png)

---

### 2. Évolution des cours (base 100 — 2013–2022)
![Évolution des cours](fig2_cours.png)

---

### 3. Profil Rendement / Risque
![Profil Rendement Risque](fig3_profil.png)

---

### 4. Matrice de corrélation
![Matrice de corrélation](fig4_corr.png)

---

### 5. Frontière efficiente de Markowitz
![Frontière efficiente](fig5_frontiere.png)

> ⭐ Le point rouge indique le **Portefeuille à Variance Minimale (PMin)** — portefeuille retenu.

---

### 6. Bêtas et R² — Modèle de Sharpe
![Bêtas et R2](fig6_beta_r2.png)

---

### 7. Régression Diageo (DGE) sur FTSE 100
![Régression Diageo](fig7_reg_diageo.png)

---

### 8. Régression Rentokil (RTO) sur FTSE 100
![Régression Rentokil](fig8_reg_rentokil.png)

---

### 9. Composition du portefeuille optimal (Elton-Gruber)
![Composition portefeuille](fig9_pie.png)

> Seuil optimal **C\* = 0,054** — Poids positifs uniquement affichés

---

### 10. NAV — Valeur liquidative historique (2013–2022)
![NAV Performance](fig10_nav.png)

---

### 11. Drawdown des portefeuilles
![Drawdown](fig11_drawdown.png)

---

### 12. Suivi de performance — Mars 2026
![Mars 2026](fig12_mars2026.png)

---

## 🏆 Résultats clés

| Portefeuille | Rendement annualisé | Volatilité | Performance mars 2026 |
|---|---|---|---|
| FTSE 100 (benchmark) | +2,10% | 15,96% | **−5,95%** |
| PMin Markowitz | +5,27% | 15,54% | **−2,87%** |
| PMin Sharpe | +5,68% | 15,97% | **−3,40%** |

> En mars 2026, le portefeuille PMin Markowitz a perdu **2 fois moins** que le marché, validant l'efficacité de l'optimisation de Markowitz en période de stress.

---

## 🛠️ Outils utilisés

- **Microsoft Excel** — Solver, Analyse ToolPak, régressions
- **Python** — pandas, numpy, matplotlib
- **LaTeX** — rédaction du rapport (pdflatex, 16 pages)
- **PowerPoint** — présentation orale (13 diapositives)

---

*Projet réalisé dans le cadre du cours de Gestion de Portefeuille — Master 1 MBFA — Université Sorbonne Paris Nord — 2025/2026*
