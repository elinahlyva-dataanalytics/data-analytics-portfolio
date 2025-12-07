# Titanic Projekt – Analyse historischer Passagierdaten

Dies ist eine spannende Aufgabe zur Analyse historischer Daten. Mit Hilfe von Bibliotheken wie NumPy, Pandas, Matplotlib und Seaborn wurden Informationen über Passagiere der legendären Titanic untersucht – einem Schiff, das im Jahr 1912 unterging.  
Der verwendete Datensatz `titanic` ist bereits in der Seaborn-Bibliothek enthalten und kann direkt importiert werden, ohne dass zusätzliche Downloads notwendig sind.


**📌 Ziel dieses Projekts** war es, die Titanic-Passagierdaten systematisch zu bereinigen, analysieren und visuell aufzubereiten, um mögliche Muster und Faktoren zu identifizieren, die die Überlebenschancen beeinflussten.


**🛠️ Verwendete Tools und Technologien:**
- Google Colab (Jupyter Notebook Umgebung)
- Python
- NumPy
- Pandas
- Seaborn
- Matplotlib


**🧩 Hauptschritte der Analyse**
1. Laden und erste Sichtung des Datensatzes `titanic` aus Seaborn.
2. Überprüfung der Datentypen und Erkennung potenziell umzuwandelnder Spalten.
3. Untersuchung auf fehlende Werte und Duplikate; Entfernung doppelter Einträge.
4. Erstellung einer neuen Spalte zur Anzahl der Verwandten an Bord; ursprüngliche Spalten wurden entfernt.
5. Visualisierung der Verteilung der Verwandtenanzahl mittels `sns.countplot`.
6. Kategorisierung von Passagieren mit mehr als 5 Verwandten als `"above 5"`.
7. Statistische Analyse der neuen Spalte nach Kategorien.
8. Auffüllen fehlender Alterswerte durch den Median.
9. Kategorisierung des Alters in Gruppen: unter 14, 14–34, 35–59, 60+ Jahre.
10. Analyse der Sterblichkeit nach Alterskategorie mithilfe boolescher Transformation und Berechnung relativer Anteile.
11. Visualisierung als Tortendiagramm, um Unterschiede zwischen absoluten und relativen Werten zu erkennen.
12. Erweiterte Kreuzanalyse der Sterblichkeit nach Alter, Ticketklasse, Decklevel und Familienanzahl.
13. Visualisierung mit Heatmaps, um relevante Muster aufzudecken.


**📊 Ergebnisse & Erkenntnisse (Heatmap-Auswertung)**

1. Alter 35–59 & 1. Klasse: höchste Sterblichkeitsrate (8 %). In der 2. Klasse überlebten anteilig die meisten Passagiere.
2. Decks C, D, E: Höchste Sterblichkeit, insbesondere bei 14–34-jährigen auf Deck C.
3. Alleinreisende zwischen 35–59 Jahren: größte Anzahl an Todesfällen. Keine Todesfälle bei Passagieren mit mehr als 5 Verwandten – familiäre Begleitung war ein starker Überlebensfaktor.
4. Geschlecht: Männer in der Altersgruppe 35–59 hatten die höchste Sterblichkeit. Alle Frauen über 60 Jahre und Jungen unter 14 konnten gerettet werden.


**📁 Projektstruktur**

- `titanic_passagier_analyse.ipynb` – Hauptnotebook mit kommentiertem Code
- `README.md` – Diese Projektdokumentation


**📌 Zusammenfassung**

Dieses Projekt zeigt, wie historische Daten durch systematische Datenbereinigung, Feature Engineering und Visualisierung analysiert werden können, um aussagekräftige Muster und Entscheidungsfaktoren zu erkennen.  
Besondere Aufmerksamkeit wurde der Kombination von Alterskategorie, sozialem Status (Klasse), Familienstand und Geschlecht in Bezug auf die Überlebenswahrscheinlichkeit gewidmet.


📍 Erstellt und ausgeführt in Google Colab  
🔗 Autorin: Elina Hlyva, https://github.com/elinahlyva-dataanalytics  
📅 Projektzeitraum: November 2025

