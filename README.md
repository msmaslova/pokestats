# PokeStats: Pokemon Data Analysis 📈

## About

This project analyzes Pokemon data using Python and Jupyter Notebook.  
The goal is to clean the data, create new features like "Total Stats" and "Speed Category," and visualize key insights such as attack vs defense and speed distributions.

## Project Structure

```
pokestats/
├── data/
│   └── pokemon.xlsx          # Raw data
├── notebooks/
│   └── PokeCode.ipynb   # Jupyter Notebook with cleaning and visualizations
├── README.md                 # Project description
```


## Technologies Used

- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook
- Tableau for additional dashboard

## How to Run

1. Open `PokeCode.ipynb` in Jupyter Notebook.
2. Run all cells sequentially.
3. View the generated visualizations.

## Key Features

- Data cleaning and duplicate removal
- Creating a "Total Stats" feature by summing major Pokemon characteristics
- Speed categorization: Fast, Average, Slow
- Visualizations:
  - Total Stats distribution
  - Attack vs Defense scatter plot
  - Top 10 Pokemon by overall strength

## Visualization

<p align="center">
  <img src="images/TotalStats.png" alt="Total Stats Distribution" width="45%" style="display:inline-block; margin-right: 10px;"/>
  <img src="images/AttackDefence.png" alt="Attack vs Defense" width="45%" style="display:inline-block;"/>
</p>

## Top-10 Pokemons

<img src="images/Top10.png" alt="Top-10" width="45%" style="display:inline-block; margin-right: 10px;"/>

## Key Insights

- Most Pokemons have moderate total stats (~400-500), with few reaching 600+.
- Attack vs Defense analysis shows that few Pokemon are extremely strong in both.
- Speed categorization helps distinguish between fast sweepers and defensive tanks.
- Legendary Pokemon significantly outperform non-legendary ones across all attributes.

## Interactive Dashboard

Explore the interactive Pokemon dashboard built with Tableau!

Key features:
- Top 10 Pokemon by Total Stats
- Attack vs Defense scatter plot (colored by Speed)
- Distribution of Total Stats among Pokémon
- Bonus! Pokemon type distribution (Bubble Chart)

The dashboard allows dynamic filtering by Speed Category (Fast, Average, Slow) and Primary Type, helping to explore different Pokémon battle strategies visually.

You can find the Tableau dashboard file in the `tableau/` folder as `pokestats_dashboard.twb`.


## Author

Created by Mariia Maslova
