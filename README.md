# Mars Planet Mission – Data Engineering Challenge 🚀

This project showcases a data engineering pipeline using web scraping and MongoDB to gather and display up-to-date information about Mars.

## 📌 Project Objective
To develop a fully functional Flask application that:
- Scrapes the latest Mars news and images from multiple sources
- Stores the data in a MongoDB database
- Displays the scraped content dynamically through an HTML dashboard

## 🛠️ Tools & Technologies
- **Python** – Scripting and automation  
- **BeautifulSoup & Splinter** – Web scraping tools  
- **Pandas** – Data manipulation and transformation  
- **Flask** – Web framework for building the front-end interface  
- **MongoDB** – NoSQL database to store and retrieve scraped content  
- **HTML/CSS** – Front-end layout and design

## 📊 Features
- Scrapes NASA Mars news titles and paragraphs  
- Retrieves Mars facts and formats them as an HTML table  
- Collects Mars hemisphere images and titles  
- Stores all data into a MongoDB database  
- Serves the data via a Flask-powered web page

## 🚀 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/hillz246/Module-11-Challenge---Mars-Planet.git
cd Module-11-Challenge---Mars-Planet
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Scraper
```bash
python scrape_mars.py
```

### 5. Launch the Flask App
```bash
flask run
```

### 6. View in Browser
Open your browser and go to:
```
http://localhost:5000
```

## 📁 Project Structure
```
├── app.py                  # Main Flask application  
├── scrape_mars.py          # Web scraping logic  
├── templates/              
│   └── index.html          # Web interface template  
├── static/                 # CSS or image files (if any)  
├── requirements.txt        # Python dependencies  
└── README.md               # Project documentation
```

## 🧠 What I Learned
- Built an ETL pipeline using Python, BeautifulSoup, and MongoDB  
- Connected a dynamic backend to a Flask-based front-end  
- Strengthened full-stack Python development and web scraping skills

## 📬 Contact
**Prachi Patel**  
[LinkedIn](https://www.linkedin.com/in/prachi-patel-030b2897/)  
*Open to roles in Data Analytics | Healthcare Analytics | Business Intelligence*


