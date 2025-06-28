# 📊 Factor Strategy Backtest – Momentum

Ce projet implémente une stratégie factorielle **Momentum** sur un univers de 10 actions américaines, à partir de données Yahoo Finance.

---

## 📁 Structure du projet

- `notebook/` → Notebook principal `factor_backtest_skeleton.ipynb`
- `requirements.txt` → Dépendances Python

---

## ⚙️ Méthodologie

1. Téléchargement de données boursières via `yfinance`
2. Calcul du facteur **momentum** (performance à 12 mois décalée)
3. Sélection du top 20 % des actions (Q5)
4. Construction du portefeuille et calcul des rendements mensuels
5. Analyse des performances : **Sharpe**, volatilité, drawdown, courbe de capital

---

## 📈 Résultats

- **Rendement annuel** ≈ 8.98 %
- **Volatilité** ≈ 7.29 %
- **Sharpe Ratio** ≈ 1.23
- **Drawdown max** ≈ -10.39 %
