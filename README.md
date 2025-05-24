# FIFA-20-Player-Clustering-
FIFA 20 Player Clustering &amp; Talent Analysis groups players using machine learning based on their in-game attributes. It reveals player similarities, potential talent clusters, and supports smarter scouting decisions.
⚽ FIFA 20 Player Clustering & Talent Analysis
This data science project leverages unsupervised machine learning techniques to group FIFA 20 players based on their in-game attributes. The goal is to uncover hidden patterns, group similar player types, and provide insights useful for scouting, team building, and gameplay strategy.

📌 Project Overview
In football (soccer), understanding player roles and identifying talent is key to building a competitive team. This project uses clustering algorithms like K-Means to group FIFA 20 players into meaningful categories based on their attributes such as pace, shooting, passing, dribbling, defending, and physicality.

Objectives:
Cluster players based on performance and physical attributes.

Visualize and interpret player groups.

Identify potential talent based on underrepresented clusters.

Support scouts, managers, analysts, and gamers with actionable insights.

📊 Dataset
Source: FIFA 20 Complete Player Dataset

Size: ~18,000+ players

Attributes Used (selected):

Pace, Shooting, Passing, Dribbling, Defending, Physical

Age, Value, Wage, Work Rate

Preferred Foot, Position, Nationality

🛠️ Technologies Used
Languages: Python 3

Libraries:

Pandas, NumPy for data handling

Matplotlib, Seaborn, Plotly for data visualization

Scikit-learn for clustering and dimensionality reduction

Yellowbrick for cluster validation

t-SNE / PCA for visualizing high-dimensional data

🔍 Clustering Techniques
K-Means Clustering

Elbow Method and Silhouette Score to determine optimal number of clusters

Principal Component Analysis (PCA) for dimensionality reduction

t-SNE for 2D cluster visualization

🏗️ Project Structure
bash
Copy
Edit
fifa20-player-clustering/
│
├── data/                  # Dataset CSV files
├── notebooks/             # Jupyter Notebooks for analysis
├── images/                # Visualizations and cluster plots
├── scripts/               # Modular clustering code
├── README.md              # Project overview
├── requirements.txt       # Required Python libraries
└── main.py                # Main clustering script
📈 Results & Insights
Players were successfully grouped into clusters such as:

Defensive players (strong physical & defending)

Creative midfielders (high passing & vision)

Fast wingers (high pace & dribbling)

Talented youngsters (low value, high potential)

Visualizations revealed trends by position, age, and market value.

Clusters can assist in identifying undervalued or emerging talent.

🚀 How to Use
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/fifa20-player-clustering.git
cd fifa20-player-clustering
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Main Script or Open Notebook
bash
Copy
Edit
python main.py
Or explore interactively via Jupyter:

bash
Copy
Edit
jupyter notebook notebooks/fifa_clustering_analysis.ipynb
📌 Visualizations
Key visualizations include:

Attribute distributions

Cluster membership scatter plots (PCA, t-SNE)

Radar charts for cluster profiles

Cluster size and average player value comparisons

<p align="center"> <img src="images/tsne_clusters.png" width="600" alt="Cluster Visualization (t-SNE)"> </p>
💡 Future Improvements
Integrate FIFA 21/22 data for trend comparison

Include potential rating and growth forecast

Develop a web dashboard for interactive talent exploration

Add supervised learning for price or rating prediction

🤝 Contributing
Contributions are welcome! Feel free to fork this repo and submit a pull request for improvements, bug fixes, or feature additions.

📄 License
This project is licensed under the MIT License.

🙏 Acknowledgements
Kaggle Dataset by Stefano Leone

Scikit-learn

Plotly

FIFA Analytics Community

