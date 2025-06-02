# BINA_FS2025
# Analyse des Schweizer Wohnimmobilienmarkts (2015–2025)

## Zweck des Projekts

Dieses Projekt widmet sich einer umfassenden Analyse der Dynamik des Schweizer Wohnimmobilienmarkts, mit einem Fokus auf Einfamilienhäuser, Zinssätze und Reallöhne im Zeitraum von 2015 bis 2025. Dabei werden auch Prognosen bis 2030 erstellt.

**Ziel** ist es, fundierte und umsetzbare Erkenntnisse für verschiedene Stakeholdergruppen bereitzustellen:

- **Politische Entscheidungsträger** (z. B. Zinsanpassungen und geldpolitische Entscheidungen)
- **Projektentwickler** (z. B. nachhaltige und resiliente Projektplanungen)
- **Investoren** (z. B. optimales Markt-Timing für Investitionen)
- **Risikomanager** (z. B. Stresstest-Szenarien und Risikobewertungen)

Beispielhafte Erkenntnisse:
- Korrelation von **0.74** zwischen Zinssätzen und Preisindex
- Erhöhte **Marktvolatilität nach 2020**

---

## Projektüberblick

Dieses Repository stellt ein interaktives **Jupyter Notebook (`work.ipynb`)** zur Verfügung, das eine systematische und datengetriebene Analyse ermöglicht.  

### Datengrundlage:

Die Daten stammen aus zwei offiziellen Quellen:

- **Schweizerische Nationalbank (SNB)**
- **Bundesamt für Statistik (BFS)**

### Inhalt des Notebooks:

#### 📁 Datenquellen
- Immobilienpreisindex (SNB, Einfamilienhäuser)
- Zinssätze (SNB)
- Reallöhne (BFS)

#### 🧪 Analytische Methoden
- Regressionsmodelle (z. B. R² = 0.5547)
- Residuenanalyse
- Zeitverzögerungsmodelle

#### 📊 Visualisierungen
- **20 statische Diagramme**: Trends, Scatterplots, Korrelationen
- **6 interaktive Plotly-Diagramme**
- **4 Tabellen** mit kompakten KPIs

---

## 📈 Mini-Dashboard

Ein Balkendiagramm vergleicht Schlüsselkennzahlen für die Zeiträume **2015–2025** und **2020–2025** – zur schnellen Orientierung und Ableitung kurzfristiger Strategien.

---

## 🎯 Empfehlungen und Handlungsempfehlungen

Maßgeschneidert für verschiedene Zielgruppen:

### 🏛️ Politische Entscheidungsträger
- Zinssteuerung
- Nachhaltige Baupolitik

### 🏗️ Projektentwickler
- Berücksichtigung von Basel III
- Planung resilienter Wohnprojekte

### 💼 Investoren
- Optimale Markteintritte
- Diversifikation

### ⚠️ Risikomanager
- Stresstest-Szenarien
- Risikoabschätzung bei Volatilität

---

## 🚀 Erste Schritte

### Voraussetzungen

- Python **3.11 oder höher**
- Jupyter Notebook oder JupyterLab

### Python-Bibliotheken:

```bash
pip install pandas numpy matplotlib seaborn plotly statsmodels
