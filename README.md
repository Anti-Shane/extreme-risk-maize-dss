# Extrême Risk Maïs : Système d'Aide à la Décision (DSS)

[cite_start]Ce projet, développé dans le cadre du concours **Make IT Agri 2026**, propose une approche disruptive pour la gestion des risques climatiques dans la filière maïsicole française[cite: 1, 9].

## 🧬 Moteur Physiologique (Standard FAO-56)
[cite_start]Le système s'appuie sur une modélisation dynamique de la réponse biologique pour sécuriser la continuité d'exploitation face aux seuils de rentabilité (7 t/ha)[cite: 11, 13]:
* [cite_start]**Développement Phénologique :** Indexation par cumul de degrés-jours (GDD base 6°C) pour une localisation précise de la fenêtre de floraison[cite: 14, 16].
* [cite_start]**Facteur de Stress ($K_s$) :** Simulation de la fermeture stomatique basée sur le bilan hydrique entre la Réserve Utile (RU) et l'évapotranspiration[cite: 19, 20].

## 📈 Optimisation Stochastique (CVaR)
[cite_start]L'innovation réside dans le passage d'une gestion "Moyenne-Variance" à une gestion du **Tail Risk** (risque de queue) via le **Conditional Value at Risk (CVaR)** à $\alpha=5\%$[cite: 43, 45]. 
* [cite_start]**Objectif :** Maximiser l'arbitrage phénologique pour tronquer la zone de ruine économique[cite: 53, 77].

## 📁 Structure du Dépôt
* `maisprototype.py` : Moteur de calcul Python (Simulation & Optimisation).
* `maisprototype.ipynb` : Version interactive (Google Colab) pour la visualisation des résultats.
* `maisk 2403.pdf` : Livre blanc technique détaillant la méthodologie et les impacts sociaux[cite: 83].
* `requirements.txt` : Dépendances pour l'environnement de calcul.

---
[cite_start]**Shane Tao (Eaton Ash)** - Candidat Make IT Agri 2026 [cite: 2]
