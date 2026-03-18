# Dakar Weather Data Analysis 🌍🌦️

## Overview

This project analyzes weather data for **Dakar, Senegal** using Python and PostgreSQL.
The goal is to store weather data in a database, analyze it using data science tools, and visualize trends.

The project demonstrates how to build a small **data pipeline** from database storage to data visualization.

---

## Features

* Store weather data in a **PostgreSQL database**
* Retrieve data using Python
* Analyze weather metrics using **Pandas**
* Visualize trends using **Matplotlib**

---

## Technologies Used

* Python
* PostgreSQL
* Pandas
* Matplotlib
* Psycopg2

---

## Project Structure

```
weather-dakar-project
│
├── projet_meteo_dakar.ipynb     # Jupyter notebook for data analysis
└── README.md
```

---

## Installation

Clone the repository:

```
git clone https://github.com/Fadall/projet_meteo_dakar.git
```

Navigate into the project folder:

```
cd projet_meteo_dakar
```

Install dependencies:

```
pip install pandas matplotlib psycopg2
```

---

## Database Configuration

Update the database configuration in the script (i used Render):

```
DB_CONFIG = {
    "host": "your_host",
    "port": "5432",
    "database": "your_database",
    "user": "your_user",
    "password": "your_password",
    "sslmode": "require"
}
```

---

## Example Visualization

The project generates visualizations such as:

* Temperature trends
* Weather variations over time
* Basic statistical analysis of weather data

---

## Future Improvements

* Automate weather data collection using an API
* Build a dashboard for real-time visualization
* Apply machine learning for weather prediction

---

## Author

Mohamed El Fadilou KEBE
