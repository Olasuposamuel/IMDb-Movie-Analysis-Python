# IMDb Movie Analysis using Python

## Project Overview
This project explores and analyzes movie industry trends using the IMDb/TMDB movie dataset with Python in Jupyter Notebook. The analysis focuses on understanding movie performance through revenue, profit, genres, directors, and release trends.

The goal of this project is to uncover insights that can help stakeholders understand what drives movie success and profitability.

---

## Objectives
The analysis answers key business questions such as:

- Which movie genres are the most common?
- Which movies generated the highest revenue?
- Which directors produced the most profitable movies?
- What factors influence movie profitability?
- Which genres dominate the movie industry?

---

## Tools & Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Dataset Information
The dataset contains information about movies, including:

- Movie titles
- Genres
- Budget
- Revenue
- Release date
- Directors
- Cast
- Production companies

The dataset was cleaned and transformed before analysis.

---

## Data Cleaning Process
The following cleaning steps were performed:

- Removed duplicate records
- Handled missing values
- Converted date columns to datetime format
- Split genre and cast columns for easier analysis
- Removed low-utility columns
- Created a new profit column:

profit = revenue - budget

---

## Exploratory Data Analysis (EDA)
The exploratory data analysis focused on identifying trends, patterns, and relationships within the movie dataset. Various analyses and visualizations were performed to better understand movie performance, revenue generation, genre popularity, and profitability.

The analysis includes:

- Revenue Analysis
- Genre Analysis
- Profitability Analysis
- Director Performance Analysis
- Budget vs Revenue Analysis
- Movie Trend Visualizations

---

## Key Insights
 - Action and Drama are among the most common movie genres.
 - High-budget movies generally generate higher revenue.
 - Some movies achieve high revenue but lower profitability due to production costs.
 - Certain directors consistently produce commercially successful movies.
 - Profitability depends on both revenue generation and budget control.

---

## Visualizations

### Revenue Analysis
![Revenue Chart](<img width="984" height="584" alt="Revenue" src="https://github.com/user-attachments/assets/05ce4563-ce00-4a6b-940a-5377d6010a42" />
)

### Genre Analysis
![Genre Chart](<img width="984" height="584" alt="Genre" src="https://github.com/user-attachments/assets/c8d00082-d027-40f3-a485-6a0c68149959" />
)

### Profit Analysis
![Profit Chart](<img width="984" height="584" alt="Profit" src="https://github.com/user-attachments/assets/2855b499-b2b6-4b4a-b08d-aa20f413a195" />
)

---

## How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/yourusername/imdb-movie-analysis-python.git
```

2. Navigate to the project folder

```bash
cd imdb-movie-analysis-python
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open the `imdb.ipynb` notebook and run all cells to view the analysis and visualizations.

---

## Conclusion

This project demonstrates practical data analysis skills using Python and Jupyter Notebook. It highlights the ability to clean data, perform exploratory analysis, create visualizations, and communicate business insights effectively.
