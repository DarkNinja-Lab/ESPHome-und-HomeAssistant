# ⚡ ESPHome & Home Assistant – Config Repository

Zentraler Hub für meine komplette Home-Automation-Konfiguration.  
Sensible Werte sind konsequent durch **XXXXXXXXXXXX** abstrahiert – Setup bleibt nachvollziehbar, ohne Risiken.

---

## 📁 Repository Structure

### 🏠 Home Assistant (Root)

- **configuration.yaml**  
  Core-Setup, Integrationen, globale Defaults, Custom Sensoren... 

- **scenes.yaml**  
  Licht- und Umfeldszenen

- **automations.yaml**  
  Event-/State-basierte Automationen

- **influx.yaml**  
  Metrics-Pipeline nach InfluxDB  
`

---

### 🔌 ESPHome (./esphome)

Strukturiert nach Geräten und Räumen.

- **/devices/** – Einzelene Geräte  
- **/rooms/** – Raumkontexte wie Lighting, Klima, Präsenz  

---

## 🎯 Guiding Principles

- **Modular & Reusable** – YAML sauber segmentiert, hoher Wiederverwertungsgrad  
- **Single Source of Truth** – klare, konsistente Automationsbasis  
- **Security-First** – keinerlei Tokens oder Credentials im Repo

---


## 📝 Notes

- Nicht als Plug-and-Play gedacht  
- Platzhalter immer durch valide Werte ersetzen  
- Inhalte bilden mein persönliches Setup ab – Anpassungen erwünscht

---

Wenn du willst, packe ich dir noch Badges, ein TOC oder Screenshots vom Setup rein.
