# ICC World Cup 2023 Player Performance Analysis 

This project dives into the performances of players in the ICC World Cup 2023 using data-driven insights and visualizations. We explore how different players performed with respect to their strike rates, boundary percentages, clusters based on similar characteristics, and more.

##  Dataset
The dataset used includes player-level information from the ICC World Cup 2023, such as:
- Player name
- Runs scored
- Balls faced
- Number of boundaries (4s and 6s)
- Strike rate
- Dismissals
- Match-wise performance

##  Goal of the Project
To analyze and cluster player performances using machine learning techniques to identify patterns, top performers, and generate key insights based on:
- Strike Rate
- Boundary Percentage
- Batting Average
- Total Runs

##  Methodology
1. **Data Cleaning & Preprocessing**
   - Handled missing values
   - Converted dismissals into a binary column to calculate batting averages
   - Computed derived stats like strike rate, boundary percentage, and batting average

2. **Feature Engineering**
   - Normalized features using `StandardScaler`
   - Handled missing values using `SimpleImputer`

3. **Clustering**
   - Applied K-Means Clustering
   - Used Elbow Method to determine optimal number of clusters

4. **Visualization**
   - Created scatter plots of strike rate vs. boundary percentage
   - Color-coded clusters for easy interpretation
   - Labeled top 20 players by total runs

##  Key Visualizations
- **Elbow Method Plot:** Helps identify optimal number of clusters
- **Clustered Scatter Plot:** Visualizes clusters based on strike rate and boundary percentage
- **Top 20 Players Plot:** Highlights performance of top players with names labeled

##  Insights
- Players were grouped into performance-based clusters
- Top players showed high strike rates and boundary percentages
- Clustering helped visualize similarities between player styles

##  How to Run the Project
1. Clone the repository
2. Open `World Cup 2023.ipynb` in Jupyter Notebook or VS Code
3. Run all cells to reproduce the analysis and plots
##  Requirements
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

Install all packages using:
```bash
pip install -r requirements.txt
```

##  Future Improvements
- Add player performance trends over time
- Include bowling statistics for all-round analysis
- Develop a simple dashboard for better interactivity

