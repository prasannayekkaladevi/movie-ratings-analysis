🎬 Movie Ratings Analysis (IMDb Top 1000)


Overview
This project analyzes the IMDb Top 1000 movies dataset to extract insights about ratings, genres, directors, and trends over time.


📂 Project Structure


movie-ratings-analysis/
│
├── data/ # Dataset (CSV)
├── notebooks/ # Jupyter/Colab notebooks
├── visualizations/ # Plots and charts
├── requirements.txt # Python dependencies
└── README.md # Project documentation




Tools & Libraries
- Python (pandas, numpy)
- Visualization: Matplotlib, Seaborn
- Platform: Google Colab
- Version Control: GitHub


Steps Performed
1. Data Cleaning:
   - Removed missing values
   - Converted data types
   - Normalized genres
2. Exploratory Data Analysis (EDA):
   - Rating distributions
   - Genre trends
   - Correlation analysis
3. Visualizations:
   - Histograms, boxplots, scatter plots
   - Correlation heatmap
4. Key Insights extraction


Key Insights
- Average IMDb rating: ~8.2
- Most frequent genre: Drama
- Biography and History genres have the highest median ratings
- Votes and Gross earnings are strongly correlated
- Ratings stayed consistent across decades


How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-ratings-analysis.git


2. Install all the dependencies
– pip install -r requirements.txt


3. Open the notebook in Google Colab or Jupyter and run all cells.