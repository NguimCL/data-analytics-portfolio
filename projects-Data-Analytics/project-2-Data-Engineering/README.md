##  Skalierbare Open-Source-Plattform für Echtzeit-Datenverarbeitung und Visualisierung

###  Projektübersicht

Entwicklung eines Systems zur Echtzeit-Datenaufnahme, -verarbeitung und -visualisierung unter Verwendung moderner Open-Source-Technologien.   
Ziel des Projekts ist der Aufbau einer modularen und erweiterbaren Data-Engineering-Plattform, die sich flexibel in unterschiedliche Umgebungen integrieren lässt.   

---

###  Verwendete Technologien

- **Apache Kafka** – Streaming und Messaging  
- **Apache Airflow** – Orchestrierung von Datenpipelines  
- **Apache Spark** – Verteilte Datenverarbeitung  
- **Great Expectations** – Datenvalidierung und Qualitätssicherung  
- **PostgreSQL** – relationale Datenspeicherung & Metadaten  
- **Docker / Docker Compose** – Containerisierung  
- **Grafana** – Datenvisualisierung  

---

###  Architektur

<p align="center">
  <img src="datenarchitekt_os.png" alt="Data Engineering OS Architektur" width="700"/>
</p>


Die Architektur basiert auf einem modularen Baukastenprinzip.  
Jeder Bestandteil (Ingestion, Processing, Storage, Monitoring) ist entkoppelt, um Wiederverwendbarkeit und Austauschbarkeit zu ermöglichen.

---

### Projektziele

- Standardisierte und automatisierte Datenverarbeitung  
- Unterstützung von Batch- und Echtzeitverarbeitung  
- Integrierte Datenqualitätssicherung  
- Visualisierung aktueller Daten in Dashboards  
- Einsatz ausschließlich quelloffener Komponenten



<p align="center">
<figcaption>Streaming-Ingestion</figcaption>
  <img src="Streaming-Ingestion.png" alt="Ingestion" width="700"/>
</p>


<p align="center">
<figcaption> Schreiben </figcaption>
  <img src="Streaming.png" alt="Streaming" width="700"/>
</p>


<p align="center">
<figcaption>Datenbank</figcaption>
  <img src="Datenbank.png" alt=" Datenbank" width="700"/>
</p>

<p align="center">
<figcaption>Echzeit  Visualisierung</figcaption>
  <img src="Visualizierung_grafana.png" alt=" Visualisierung" width="700"/>
</p>