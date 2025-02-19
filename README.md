# LG Help Center Web Scraper  

## 📌 Project Overview  
This project automates web scraping of the LG Help Center to extract support articles, themes, error codes, and related information. It utilizes **Selenium, Pandas, and Requests** to navigate pages, filter duplicate data, and store the results in structured CSV and JSON formats.  

## 🚀 Features  
✅ Extracts help article titles and links from the LG support library  
✅ Navigates through multiple pages automatically  
✅ Filters duplicate links and organizes structured data  
✅ Scrapes themes, categories, and error codes from individual articles  
✅ Downloads images and collects YouTube video links  
✅ Saves data in CSV and JSON formats  

## 📂 Folder Structure  
```
lg-help-webscraper/
│── data/                   # Contains extracted and cleaned CSV files  
│── images/                 # Stores downloaded images from articles  
│── output/                 # Stores final JSON output  
│── webscraper.py           # Main scraping script  
│── requirements.txt        # List of dependencies  
│── README.md               # Project documentation  
```

## 🛠️ Setup & Installation  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/yourusername/lg-help-webscraper.git
cd lg-help-webscraper
```

### 2️⃣ Install Dependencies  
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Scraper  
```sh
python webscraper.py
```

## 🏗️ Technologies Used  
- **Selenium** – Automated web navigation and data extraction  
- **Pandas** – Data processing and cleaning  
- **Requests** – Handling HTTP requests  
- **CSV & JSON** – Data storage formats  

## ⚡ Future Improvements  
- Expand scraping to other LG product categories  
- Implement API integration for real-time updates  
- Optimize scraping speed and error handling  

---

📌 **Developed by:** Shrinjita Paul  
🔗 [LinkedIn](https://linkedin.com/in/shrinjitapaul) | [GitHub](https://github.com/Shrinjita)  
```
