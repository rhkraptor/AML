# 🌪️ Prädiktive Wartung von Windkraftanlagen mit Machine Learning

**Autor:** Hussnain Khalil  
**Kurs:** Applied Machine Learning
**Datum:** 16. Januar 2025  
**E-Mail:** huk7464@thi.de

---

## 📌 Projektbeschreibung

Dieses Projekt beschäftigt sich mit der Entwicklung eines Machine-Learning-Modells zur **prädiktiven Wartung** von Windkraftanlagen unter Verwendung realer SCADA-Daten.

Ziel ist es, mithilfe fortgeschrittener Datenanalyse und Klassifikationsmodelle (z. B. Decision Tree, Random Forest, XGBoost) potenzielle Fehler frühzeitig zu erkennen und somit Ausfallzeiten und Wartungskosten zu minimieren.

---

## 📁 Projektstruktur

| Datei                          | Beschreibung                                                                 |
|-------------------------------|------------------------------------------------------------------------------|
| `AML_Projekt.ipynb`           | 🧠 Hauptprojekt-Notebook mit Code zur Datenanalyse, Modelltraining & Visualisierung |
| `pred_maint_wind.csv`         | 📊 Verwendeter SCADA-Datensatz mit Betriebsdaten der Windkraftanlagen       |
| `2025_AML_Ausarbeitung.pdf`   | 📄 Schriftlicher Projektbericht

---

## 🔍 Hauptinhalte des Projekts

- **Ziel:** Klassifikation von Fehlern (Error = 1) vs. Normalbetrieb (Error = 0)
- **Datenquelle:** SCADA-Daten von Windkraftanlagen (`pred_maint_wind.csv`)
- **EDA:** Visualisierung, Feature Engineering, Ausreißerbehandlung
- **Modellierung:** Decision Tree, Random Forest, XGBoost
- **Datenungleichgewicht:** Behebung mit **SMOTE-ENN**
- **Optimierung:** Hyperparameter-Tuning mit `GridSearchCV`
- **Metriken:** Recall, Precision, F1-Score (Fokus auf Fehlerklasse)

---

## 🚀 Ergebnisse (nach Resampling & Tuning)

| Modell        | Recall (Fehler) | Precision (Fehler) | F1-Score |
|---------------|-----------------|--------------------|----------|
| Decision Tree | 84.00 %         | 67.74 %            | 75.00 %  |
| Random Forest | 86.67 %         | 77.38 %            | 81.76 %  |
| XGBoost       | 88.00 %         | 73.33 %            | 80.00 %  |