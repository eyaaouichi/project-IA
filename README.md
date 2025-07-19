Projet d'IA pour Prédiction des Marchés Cryptos
Objectif : Développer un système intelligent d'analyse et de prédiction des prix des cryptomonnaies (BTC, XRP, XAU) en combinant backtesting, charting et modèles d'IA.



🛠️ Stack Technique
Composant	Outils/Technologies
Langage principal	Python (Jupyter Notebooks, scripts .py)
Analyse de données	Pandas, NumPy, Finta (indicateurs techniques)
Visualisation	Matplotlib/Seaborn (plot.png)
Backtesting	Backtrader ou PyAlgoTrade (backtest.ipynb)
Données	CSV/JSON (Bittrex, Poloniex, XAU-USD)
Tests	Tests unitaires (test_*.py)





📂 Structure des Fichiers & Fonctionnalités
backtest.ipynb

Simulation de stratégies de trading (ex: SMA, RSI) sur données historiques.

Calcul des performances (Sharpe ratio, drawdown).

charting.ipynb

Visualisation des prix et indicateurs (plot.png généré).

Identification de motifs graphiques (head & shoulders, triangles).

intro.ipynb

Introduction aux concepts (chargement des données, preprocessing).

Données (data/)

bittrex_btc-usdt.csv : Prix BTC/USDT (échange Bittrex).

poloniex_xrp-btc.json : Prix XRP/BTC (échange Poloniex).

xau-usd.json : Or vs USD (marché traditionnel).

Bibliothèque finta

Implémentation d'indicateurs techniques (MACD, Bollinger Bands).

Tests (test_*.py)

Validation des calculs (ex: vérification des indicateurs).




📈 Fonctionnalités Clés
Prédiction de prix : Modèles de séries temporelles (ARIMA, LSTM).

Analyse multi-marchés : Corrélation BTC/XRP/XAU.

Alertes automatisées : Détection de seuils (RSI > 70 = survente).
