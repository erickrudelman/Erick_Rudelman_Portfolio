---
date: 2023-08-08T11:00:59-04:00
description: "EPL Player Stats 21/22 Exploration App"
featured_image: "/images/liverpool_stand_2.jpg"
tags: []
title: "Chapter II: Analyzing EPL Player Stats"
---

**Function and Purpose:**
This Streamlit app provides an engaging platform to explore and analyze English Premier League (EPL) player statistics for the 2021/2022 season. It empowers users to visualize and understand player performance, correlations between different stats, and team-related insights. The app facilitates data-driven decision-making for football enthusiasts, sports analysts, and EPL fans.

**App Workflow and Features:**

1. **Sidebar User Input:**
   The sidebar allows users to interactively select clubs (teams) using a multiselect dropdown. The user's selected clubs influence the data displayed throughout the app.

2. **Data Loading and Display:**
   The EPL dataset is loaded from a CSV file, filtered to remove teams with ',' in their names, and displayed in a tabular format. Users can observe various player statistics such as goals (G), assists (A), minutes played (Min), etc.

3. **Download Data:**
   A link is provided to download the displayed data in CSV format, enabling users to save and analyze the data externally.

4. **Correlation Scatter Plots:**
   The app offers two scatter plots showcasing correlations between minutes played (Min) and either assists (A) or goals (G) for selected players. Users can choose specific players from the sidebar for comparison.

5. **Player Comparison:**
   Users can select players and a specific stat (Min, A, G) to compare. The app generates scatter plots for the selected players, showcasing their chosen stat against minutes played.

6. **Top Teams and Players:**
   The app computes and displays the top 10 teams with the most goals and assists. It also provides an option to explore top players within each top team in terms of goals and assists.

7. **Correlation Heatmap:**
   The app creates a heatmap to visualize the correlation matrix between different player statistics and team performance. Positive and negative correlations are represented by color variations.

8. **Heatmap Explanation:**
   An explanation is provided to help users interpret the heatmap, clarifying how correlation values are displayed and what different colors indicate.

**Data Science Techniques and Libraries Applied:**
- **Data Visualization:** Various visualization techniques are employed, including scatter plots, heatmaps, and tabular displays. These visualizations enable users to explore player statistics, correlations, and team performance effectively.
- **Data Analysis:** The app calculates and presents descriptive statistics such as the top 10 teams with most goals and assists, as well as top players within each team.
- **Correlation Analysis:** Correlation matrices and heatmaps are used to visually represent correlations between player statistics and team performance, helping users identify patterns and relationships.
- **Libraries:** The app harnesses libraries such as `streamlit`, `pandas`, `base64`, `matplotlib`, `seaborn`, and `numpy` to create a dynamic user interface, analyze data, and generate insightful visualizations.

In summary, this Streamlit application seamlessly blends sports fandom, data exploration, and analytics. It caters to football enthusiasts, analysts, and anyone intrigued by EPL player performance, offering a platform for interactive insights, comparisons, and discoveries within the realm of English Premier League football.


[Link to GitHub Repository](https://github.com/rudicr/data_science_projects/blob/Data-Science-Projects/EPL_stats_app.py)