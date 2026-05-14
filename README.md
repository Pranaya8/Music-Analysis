Global Beats: Tracking the Rise of Non-English Music (2018–2025)
📌 Project Overview

In the modern streaming era, music has become increasingly borderless. This project analyzes a dataset of over 8,500 Spotify tracks to quantify the "Global Crossover" effect—the transition of regional genres (Latino, K-Pop, Afrobeats) from niche markets to global chart dominance.

The goal of this analysis was to move beyond surface-level streaming counts and identify the underlying patterns of market penetration, listener loyalty, and song optimization that drive international success.
🚀 Key Insights

    Market Share Explosion: Latino/Hispanic music witnessed a 300% surge in global chart representation between 2021 and 2023, establishing itself as the primary driver of non-English growth.

    The "Star Power" Advantage: While English Pop has higher track volume, Reggaeton and K-Pop artists possess the highest "Star Power" (average followers per artist), indicating a more concentrated and loyal global fanbase.

    Predictive "Sweet Spot": Statistical analysis reveals that tracks with a duration between 2.7 and 3.4 minutes have a 20% higher probability of reaching high popularity scores, regardless of genre.

    High-Floor Popularity: Global genres exhibit a "higher floor" than mainstream English tracks, meaning international crossover hits maintain a more consistent popularity distribution with lower variance.

🛠️ Tech Stack

    Language: Python 3.x

    Data Manipulation: Pandas, NumPy

    Visualization: Seaborn, Matplotlib

    Environment: Jupyter Notebooks

📊 Visualizations
1. Growth of Global Music Categories

Description: A time-series analysis showing the percentage share of various global regions in the charts. This highlights the specific years where Latino and Asian music broke into the mainstream.
2. Artist Star Power by Genre

Description: A comparison of listener loyalty, calculated as the average number of followers per artist within a specific genre. This metric identifies which genres have the most dedicated "superfans."
3. Track Duration vs. Popularity

Description: A scatter plot identifying the correlation between song length and listener engagement, revealing the optimal duration for modern hits.
📁 Repository Structure
Plaintext

├── data/
│   └── final_music_data_analysis.csv    # The processed and cleaned dataset
├── visuals/
│   ├── crossover_trend.png               # Market share line chart
│   ├── genre_loyalty.png                # Star Power bar chart
│   └── duration_scatter.png             # Popularity vs Duration plot
├── Analysis_Notebook.ipynb               # Full Python source code and logic
└── README.md                             # Project documentation

📥 How to Run

    Clone this repository:
    Bash

    git clone https://github.com/yourusername/global-music-crossover.git

    Install dependencies:
    Bash

    pip install pandas matplotlib seaborn

    Open Analysis_Notebook.ipynb in Jupyter Notebook or VS Code and run all cells.

🧪 Data Methodology

    Data Cleaning: Handled missing artist metadata and standardized release dates across two decades.

    Feature Engineering: Developed a custom keyword-mapping algorithm to classify artists into regional market segments (Latino, Asian, European, etc.) based on nested genre tags.

    Metrics: Created the "Star Power" metric to normalize follower counts against artist volume, providing a more accurate representation of genre influence.
