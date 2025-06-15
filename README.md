# NYC Airbnb Listings 2024 - Exploratory Data Analysis

Welcome to the NYC Airbnb Listings 2024 EDA project! This repository contains a comprehensive exploratory data analysis (EDA) of Airbnb listings in New York City, providing insights into pricing, availability, host activity, and neighborhood trends.

## 📊 Project Overview

This project aims to analyze the Airbnb listings dataset for New York City to uncover patterns and insights that can help hosts, guests, and stakeholders make informed decisions. The analysis covers various aspects such as price distribution, geographical trends, host activity, and more.

## 🗂️ Dataset

- **Source:** [Inside Airbnb](http://insideairbnb.com/get-the-data.html) or Kaggle
- **File:** `AB_NYC_2019.csv` (or your dataset file)
- **Features include:**
  - `id`, `name`, `host_id`, `host_name`
  - `neighbourhood_group`, `neighbourhood`
  - `latitude`, `longitude`
  - `room_type`, `price`
  - `minimum_nights`, `number_of_reviews`
  - `last_review`, `reviews_per_month`
  - `calculated_host_listings_count`, `availability_365`

## 🔍 Analysis Performed

- **Data Cleaning:** Handling missing values, correcting data types, and removing duplicates.
- **Univariate Analysis:** Distribution of prices, room types, and minimum nights.
- **Bivariate & Multivariate Analysis:** Price trends by neighborhood, room type, and host.
- **Geospatial Analysis:** Mapping listings and price heatmaps across NYC.
- **Host Analysis:** Identifying top hosts and their activity.
- **Temporal Trends:** Availability and review trends over time.
- **Correlation Analysis:** Exploring relationships between numerical features.
- **Outlier Detection:** Identifying unusual listings or pricing.

## 📈 Key Insights

- Manhattan and Brooklyn have the highest concentration of listings.
- Private rooms are generally more affordable than entire homes/apartments.
- Certain neighborhoods command significantly higher prices.
- Some hosts manage a large number of listings, indicating professional activity.
- There are seasonal and neighborhood-based trends in availability and pricing.

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib & Seaborn** for visualization
- **Folium** for interactive maps
- **Jupyter Notebook** for analysis and reporting

## 🚀 Getting Started

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/nyc-airbnb-eda.git
   cd nyc-airbnb-eda
   ```
2. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```
3. **Run the analysis:**
   - Open the Jupyter Notebook (`.ipynb` file) in VS Code or Jupyter Lab.
   - Execute cells to reproduce the analysis and visualizations.

## 📂 Project Structure

```
NYC-AirBNB(EDA)/
│
├── data/
│   └── AB_NYC_2019.csv
├── notebooks/
│   └── nyc_airbnb_eda.ipynb
├── images/
│   └── (generated plots and maps)
├── README.md
└── requirements.txt
```

## 📌 Future Work

- Sentiment analysis of reviews
- Predictive modeling for price estimation
- Comparison with hotel prices
- Time series analysis for booking trends

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for suggestions or improvements.




