# Rental Market Analysis in Hyderabad 

Exploratory Data Analysis of Hyderabad’s rental market using web scraping, Python, and visualization.

##  Overview
This project analyzes **rental property trends in Hyderabad** using data scraped from [MagicBricks](https://www.magicbricks.com/).  
The aim is to identify **factors influencing rent**, study rent distribution across locations, and provide **data-driven insights** for tenants, landlords, and real-estate stakeholders.  

## 📊 Dataset
- **Source**: MagicBricks (scraped using Selenium + BeautifulSoup)  
- **Size**: 690 properties, 13 features  
- **Key Columns**: Type, Bedrooms, Location, Area, Furnishing, Rent, Maintenance Charges 

## ⚙️ Tech Stack
- **Python** | **Selenium** | **BeautifulSoup** | **Regex** | **Pandas** | **Matplotlib** | **Seaborn** 

## Key Highlights
- Performed **web scraping**, cleaning, and **feature engineering** (Rent per sqft, Total Monthly Charges).  
- Conducted **EDA**: rent trends by property type, furnishing, bedrooms, and locations.
- The rent levels in Hyderabad are influenced by Property type, Size, Furnishing Status and Location, with premium areas and larger, furnished properties commanding the highest rents.
- Key Insight: Premium areas (Hitech City, Gachibowli, Jubilee Hills, Banjara Hills) have the highest rents, while locations like Hayatnagar, Boduppal, Badangpet, etc offer affordable options. 
- Semi-furnished apartments dominate the market; rent per sqft decreases with larger properties.  
