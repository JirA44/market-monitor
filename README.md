# Market Monitor

## Français

**Market Monitor** est un ensemble de scripts Python qui récupèrent des données publiques de marché Hyperliquid et recherchent des configurations selon plusieurs stratégies. Il peut comparer des variations de prix, le financement, l’intérêt ouvert et le volume, puis afficher des signaux à examiner.

### À quoi ça sert, et pourquoi ?

L’outil sert à surveiller plusieurs actifs et à rassembler des indicateurs de marché dans un rapport. Il peut aider à repérer des situations qui méritent une analyse plus approfondie, sans suivre manuellement chaque actif.

### Exemple d’utilisation

Depuis la racine du dépôt, avec Python installé et une connexion Internet :

```bash
python auto_scan.py
```

Le script affiche un résumé du scan et, si des signaux dépassent son seuil interne, des propositions formatées pour examen. Pour comparer les fenêtres temporelles et les secteurs, inspecter également `enhanced_scanner.py`. Les stratégies documentées sont dans `STRATEGIES.md`.

**Limites et risques :** un signal est une hypothèse à vérifier, pas une recommandation ni une garantie de résultat. Ce dépôt ne prouve pas qu’une stratégie est rentable. Vérifier le code, les données, les paramètres et les risques avant toute décision ; ne pas envoyer d’ordres ni engager de fonds sur la seule base d’une alerte.

## English

**Market Monitor** is a set of Python scripts that retrieves public Hyperliquid market data and scans for setups using several strategies. It can compare price changes, funding, open interest, and volume, then display signals for review.

### What is it for, and why use it?

The tool helps monitor multiple assets and collect market indicators into a report. It can highlight situations for further analysis without manually following every asset.

### Example

From the repository root, with Python installed and an internet connection:

```bash
python auto_scan.py
```

The script prints a scan summary and, when signals exceed its internal threshold, formatted proposals for review. To compare time windows and sectors, also inspect `enhanced_scanner.py`. The documented strategies are in `STRATEGIES.md`.

**Limits and risks:** a signal is a hypothesis to verify, not a recommendation or a promise of results. This repository does not prove that a strategy is profitable. Review the code, data, and parameters before making decisions; do not place orders or commit funds based only on an alert.
