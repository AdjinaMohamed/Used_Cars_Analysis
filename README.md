# 🚗 Used Cars Dataset Analysis – Germany
# 🚘 Analyse von Gebrauchtwagen – Deutschland

---

## 📝 Project Overview / Projektübersicht
This project is an **exploratory data analysis (EDA)** of used cars listed on German websites.  
Ziel ist es, Trends zu erkennen, Faktoren, die den Fahrzeugpreis beeinflussen, zu verstehen und Einblicke in den Werterhalt, die Beliebtheit und die Marktmerkmale von Autos zu gewinnen.  

**Goal / Ziel:**  
- 📊 Uncover trends and understand factors affecting car prices.  
- 💡 Einblicke in Werterhalt, Beliebtheit und Marktmerkmale von Autos gewinnen.  
- 🏆 Part of a **Data Analyst portfolio**.  

---

## 📂 Dataset / Datensatz
- **Source / Quelle:** Publicly available used car listings from Germany / Öffentlich verfügbare Gebrauchtwagenangebote  
- **Size / Größe:** 44,265 entries / 44.265 Einträge, 9 columns / 9 Spalten  
- **Columns / Spalten:**  
  - `mileage` – Total kilometers driven / Gesamtkilometerstand  
  - `brand` – Car manufacturer / Automarke  
  - `model` – Car model / Automodell  
  - `fuel` – Fuel type (Gasoline, Diesel, Electric) / Kraftstoffart (Benzin, Diesel, Elektro)  
  - `transmission` – Gear type (Manual, Automatic) / Getriebeart (Schaltgetriebe, Automatik)  
  - `offerType` – Sale type (Used, New, Demonstration) / Angebotstyp (Gebraucht, Neu, Vorführwagen)  
  - `price` – Listing price in Euros / Preis in Euro  
  - `hp` – Horsepower / Pferdestärken  
  - `year` – Year of manufacture / Baujahr  

---

## 🛠 Project Steps / Projektablauf

### 1️⃣ Define Questions / Fragestellung
- Which car brands/models retain the most value? / Welche Automarken/-modelle behalten ihren Wert am besten?  
- How do factors like mileage, age, fuel type, or region affect price? / Wie beeinflussen Faktoren wie Kilometerstand, Alter, Kraftstoffart oder Region den Preis?  
- What are the most popular cars by region or price range? / Welche Autos sind nach Region oder Preisklasse am beliebtesten?  

### 2️⃣ Data Cleaning / Datenbereinigung
- ✅ Handled missing values for `model`, `transmission`, and `hp`.  
- ✏ Renamed columns for clarity (`make` → `brand`, `gear` → `transmission`).  
- 🔧 Checked and corrected data types for numeric and categorical columns.  
- 🚫 Removed or adjusted outliers for price, mileage, and horsepower.  
- 🧹 Standardized categorical text data.  

### 3️⃣ Feature Engineering / Feature Engineering
- 📅 Created **Car Age** from the year of manufacture / Fahrzeugalter berechnet aus dem Baujahr.  
- 💰 Created **Price per Horsepower** and **Price per Kilometer** for better value comparisons / Preis pro Pferdestärke & Preis pro Kilometer erstellt.  
- 🏷 Prepared categorical columns for analysis / Kategorische Spalten für Analyse vorbereitet.  

### 4️⃣ Exploratory Data Analysis (EDA) / Explorative Datenanalyse (EDA)
- 📊 Plotted distributions of numeric variables (price, mileage, hp, year) / Verteilungen numerischer Variablen visualisiert.  
- 🔍 Investigated relationships: price vs mileage, price vs car age / Beziehungen untersucht.  
- 🏎 Analyzed categorical variables: brand popularity, fuel type trends, transmission types / Kategorische Variablen analysiert.  

### 5️⃣ Insights / Erkenntnisse
- 💡 Brands/models with the best value retention / Marken/Modelle mit bestem Werterhalt.  
- 📉 Impact of mileage, age, and fuel type on price / Einfluss von Kilometerstand, Alter und Kraftstoffart auf den Preis.  
- 🌟 Popular cars by price range and region / Beliebte Autos nach Preisklasse und Region.  

---

## ⚙ Tools & Libraries / Tools & Bibliotheken
- Python 3.x  
- Pandas 🐼  
- NumPy 🔢  
- Matplotlib 📈  
- Seaborn 🎨  

---

## 🚀 How to Use / Nutzung
1. Clone the repository / Repository klonen.  
2. Open `Used_Cars_Analysis.ipynb` in Jupyter Notebook / `Used_Cars_Analysis.ipynb` in Jupyter Notebook öffnen.  
3. Run each cell in order / Jede Zelle der Reihe nach ausführen, um Datenbereinigung, Feature Engineering, Visualisierungen und Erkenntnisse zu sehen.  

---

## 👤 Author / Autor
**Adjina Med Achraf** – Data Analyst Intern Portfolio
