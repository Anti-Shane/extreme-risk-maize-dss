# Extrême Risk Maïs : Système d'Aide à la Décision (DSS)

Ce projet, développé dans le cadre du concours **Make IT Agri 2026**, propose une approche disruptive pour la gestion des risques climatiques dans la filière maïsicole française.

## 🧬 Moteur Physiologique (Standard FAO-56)
Le système s'appuie sur une modélisation dynamique de la réponse biologique pour sécuriser la continuité d'exploitation face aux seuils de rentabilité (7 t/ha):
* **Développement Phénologique :** Indexation par cumul de degrés-jours (GDD base 6°C) pour une localisation précise de la fenêtre de floraison.
* **Facteur de Stress ($K_s$) :** Simulation de la fermeture stomatique basée sur le bilan hydrique entre la Réserve Utile (RU) et l'évapotranspiration.

## 📈 Optimisation Stochastique (CVaR)
L'innovation réside dans le passage d'une gestion "Moyenne-Variance" à une gestion du **Tail Risk** (risque de queue) via le **Conditional Value at Risk (CVaR)** à $\alpha=5\%$. 
* **Objectif :** Maximiser l'arbitrage phénologique pour tronquer la zone de ruine économique.

## 📁 Structure du Dépôt
* `maisprototype.py` : Moteur de calcul Python (Simulation & Optimisation).
* `maisprototype.ipynb` : Version interactive (Google Colab) pour la visualisation des résultats.
* `maisk 2403.pdf` : Livre blanc technique détaillant la méthodologie et les impacts sociaux[cite: 83].
* `requirements.txt` : Dépendances pour l'environnement de calcul.

---
**Shane Tao ** - Candidat Make IT Agri 2026
