# French Real Estate Market Analytics Tool 

## 🚀 Overview
This repository hosts a robust **Data Extraction Pipeline** engineered to retrieve and structure property market data from regional French directories. The solution is designed for **high-reliability data aggregation**, featuring explicit wait strategies, modular exception handling, and automated CSV persistence for seamless CRM integration.

## ✨ Key Features
* **Scalable Architecture:** Dynamically ingests target regions from an external configuration file (`target_regions.csv`), allowing for campaign-based data collection.
* **Human-Like Simulation:** Utilizes advanced DOM interaction patterns to navigate complex search forms and dropdowns naturally.
* **Operational Stability:** Implements `WebDriverWait` and `expected_conditions` to handle network latency and dynamic content loading without crashing.
* **Structured Output:** Automatically formats extracted insights (Owner Name, Location, Property Type) into UTF-8 encoded CSV files tailored for business intelligence analysis.

## 🛠️ Technical Stack
* **Core Logic:** Python 3.x
* **Automation Engine:** Selenium WebDriver
* **Data Handling:** CSV Module & Logging
* **Browser:** Google Chrome (Headless compatible)

## 📂 Project Structure
```text
french-real-estate-analytics/
├── market_data_extractor.py   # Main automation pipeline logic
├── target_regions.csv         # Configuration input (Regions to process)
├── demo_data_structure.csv    # Sample output schema visualization
├── requirements.txt           # Dependency definitions
└── README.md                  # System documentation

```

## ⚙️ Installation & Usage

1. **Clone the Repository:**
```bash
git clone [https://github.com/berk-io/french-real-estate-analytics.git](https://github.com/berk-io/french-real-estate-analytics.git)
cd french-real-estate-analytics

```


2. **Install Dependencies:**
```bash
pip install -r requirements.txt

```


3. **Run the Pipeline:**
Ensure your `target_regions.csv` is configured, then execute:
```bash
python market_data_extractor.py

```



## 📊 Data Integrity

The system includes built-in logging to track the extraction process in real-time, ensuring transparency and aiding in rapid troubleshooting during large-scale data operations

---

*Note: This tool is intended for educational and market analysis purposes, adhering to ethical data extraction standards.*
