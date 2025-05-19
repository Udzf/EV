# EV

# Subject: Are Electric Cars Really Helping the Environment?

This project explores whether the rise of electric vehicles (EVs) in Switzerland has a measurable impact on air quality. Using public datasets and statistical modeling, we examine the correlation between EV adoption and pollutant emissions over time.

## Team

- Omar Abbassi  data searching, cleaning, Eda, correlation,
- Simon Chapatte data, correlation, trend , machine learning, regression

GitHub: [https://github.com/Udzf/EV](https://github.com/Udzf/EV)

---

##  Objectives

- Analyze trends in CO₂, NO₂, and PM10, emissions due to transport
- Measure how EV share correlates with pollution decline
- Compare Switzerland with Norway for context
- Look at canton-level air quality and EV sales
- Use regression models to assess relationships and potential causality
- Use prediction train model ...
- ...

---

##  Methods Used

- Exploratory Data Analysis (EDA)
- Correlation matrix & Pearson coefficient
- Simple and multivariate OLS regression
- Variance Inflation Factor (VIF) analysis
- Covariance matrix analysis
- Polynomial regression
- Lazypredict for simple and multivariatre model
- Heatmaps and regression plots

---


---

##  Project Structure ( to modify)

📁 data/ # Raw and cleaned data files
📄 README.md # This file


---

##  Key Findings

- EV share is significantly correlated with reduced transport emissions (especially CO₂ and NO₂)
- However, transport accounts for a small share of total emissions, limiting the overall air quality impact
- EV adoption alone isn’t enough — other polluting sectors matter
- No direct proof of causality, but strong signs of influence

---

##  Presentation Delivery

 A short summary video and slide deck are available in 
- youtube link
- stream lit app
- https://machine-learning-air.streamlit.app

---

##  Data Sources

**National & European Agencies:**
- [Switzerland Greenhouse Gas Inventory – FOEN](https://www.bafu.admin.ch/bafu/en/home/topics/climate/state/data/greenhouse-gas-inventory.html)
- [EDGAR – Global Greenhouse Gas Emissions Dataset](https://edgar.jrc.ec.europa.eu/dataset_ap81)
- [Worldometers – Switzerland CO₂ Emissions](https://www.worldometers.info/co2-emissions/switzerland-co2-emissions)

**Swiss Emissions, Mobility & Environment:**
- [Air quality monitoring (NABEL)](https://www.bafu.admin.ch/bafu/en/home/topics/air/luftbelastung/data/data-query-nabel.html)
- [EV registrations in Switzerland (BFS)](https://www.pxweb.bfs.admin.ch/pxweb/en/px-x-1103020100_101/px-x-1103020100_101/px-x-1103020100_101.px)
- [Public transport environmental impact (BFS)](https://www.bfs.admin.ch/bfs/fr/home/statistiques/mobilite-transports/accidents-impact-environnement/impact-environnement.assetdetail.32288019.html)
- [Stock of diesel vehicles (PX-Web)](https://www.pxweb.bfs.admin.ch/pxweb/en/px-x-1103020100_101/px-x-1103020100_101/px-x-1103020100_101.px)
- [Registered vehicles in CH (PX-Web)](https://www.pxweb.bfs.admin.ch/pxweb/en/px-x-1103020100_101/px-x-1103020100_101/px-x-1103020100_101.px)

**Swiss Climate Data:**
- [Swiss mean temperature (MeteoSwiss)](https://www.meteoswiss.admin.ch/services-and-publications/applications/ext/climate-swissmean.html)
- [Observed annual precipitation (World Bank)](https://climateknowledgeportal.worldbank.org/country/switzerland/climate-data-historical)
- [PM2.5 exposure in Switzerland (World Bank)](https://data.worldbank.org/indicator/EN.ATM.PM25.MC.M3?locations=CH)

**Canton-Level Air Quality:**
- [Luftqualitaet.ch – Swiss air data archive](https://www.luftqualitaet.ch/donnees/archive_donnees/abfrage)
- [IN-Luft – Historic air quality measurements](https://in-luft.ch/luftqualitaet/archiv_messwerte)
- [Ostluft – Annual values](https://www.ostluft.ch/messwerte/tabelle-jahreswerte)
- [Fribourg – Air quality 2023](https://www.fr.ch/dime/sen/actualites/la-qualite-de-lair-en-2023)
- [Geneva – ROPAG reports](https://www.ge.ch/document/rapports-qualite-air-geneve-ropag)
- [Bern – Air quality dashboard](https://gisapp.bern.ch/portal/apps/dashboards/62408063369b4a398250c5e5daa36287)
- [Neuchâtel – Air quality stats](https://www.ne.ch/autorites/DFS/STAT/portail-statistique/Pages/2d.html)
- [Zurich – Ostluft annual review](https://www.ostluft.ch/jahresrueckblick)

**Norway Comparison Data:**
- [EV registrations in Norway (SSB)](https://www.ssb.no/en/statbank/table/07849/)
- [Air quality – Norway (SSB)](https://www.ssb.no/en/statbank/list/klimagassn)


---

##  License ??? not necessary I guess

This project was completed as part of an academic course at Unil/EPFL Lausanne (Spring 2025).  
Usage is educational and non-commercial only.

