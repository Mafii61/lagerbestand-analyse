# Lagerbestandsanalyse – Tage bis Leerstand & Nachbestellung

## Projektziel
Ziel dieses Projekts ist die Analyse von Lagerbeständen auf Basis
aktueller Bestände, angenommener täglicher Verbrauchswerte und
Lieferzeiten, um drohende Leerstände frühzeitig zu erkennen und
Nachbestellentscheidungen zu unterstützen.

Das Projekt simuliert eine einfache, regelbasierte Lagerüberwachung.

---

## Datengrundlage
Die Analyse basiert auf einer Excel-Datei mit folgenden Spalten:

- Artikel  
- Bestand  
- Verbrauch_pro_Tag (angenommener durchschnittlicher Tagesverbrauch)  
- Meldebestand  
- Lieferzeit_Tage  

Die verwendeten Daten sind **synthetisch**, orientieren sich jedoch an
realistischen Lager- und Verbrauchsstrukturen typischer Industrie- und
Handelsunternehmen.

## Voraussetzungen
- Python 3.10+
- Git

## Setup

### 1. Repository klonen
git clone https://github.com/Mafii61/lagerbestand-analyse.git

cd lagerbestand-analyse

### 2. Virtuelle Umgebung erstellen

python -m venv env

### 3. Virtuelle Umgebung aktivieren

Windows (PowerShell):  env\Scripts\Activate.ps1

Windows (cmd):  env\Scripts\activate.bat

macOS / Linux:  source env/bin/activate

### 4. Bibliotheken installieren

pip install -r requirements.txt

### 5. Notebook starten

Bei Notebook folgende Datei starten und alle Zellen ausführen:

lagerbestands_analyse.ipynb
