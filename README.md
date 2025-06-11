# Board Game Exploratory Data Analysis (EDA)
##Project Overview
This project explores board game data from BoardGameGeek (BGG), the premier online forum and database for board game enthusiasts. The analysis focuses on understanding what makes board games successful and provides data-driven recommendations for game designers and publishers.

##Dataset Information
The dataset contains information about over 20,000 board games from BoardGameGeek, including:
- Game ratings (average and user)
- Game mechanics (e.g., dice rolling, hand management)
- Game categories (e.g., strategy, family)
- Play time
- Player count (minimum and maximum)
- Game complexity (weight)

Source: BoardGameGeek, LLC (https://boardgamegeek.com/)

Key Findings & Recommendations
After thorough data cleaning, analysis, and visualization, the following insights emerged:

- Game Mechanics: Games featuring hand management and dice rolling mechanics tend to perform well with enthusiasts
- Game Categories: Strategy games show strong popularity and engagement
- Game Duration: Optimal play time appears to be around 60 minutes
- Complexity: Games with relatively high complexity (but not extreme) tend to be well-received

*Note: These recommendations are based on general trends in the data. More advanced statistical analysis could provide deeper insights.*

Technologies Used
Python 3

Jupyter Notebook (optional)

## Python Packages Required

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

## Project Structure

```
board-game-eda/
├── BGG_Data_Set.csv/                                 # Contains dataset files
├── boardgame_eda_deck                              # Contains slides deck used for presentation
├── Technical_Notebook_Boardgame_EDA/               # Jupyter notebooks with analysis
└── README.md                                       # This file

```
##Getting Started
1. Clone this repository

2. Install required packages: pip install -r requirements.txt

3. Run the Jupyter Notebooks or Python scripts to reproduce the analysis

##Future Work
This analysis provides a foundation for deeper investigation. Potential next steps include:

- More advanced statistical modeling
- Sentiment analysis of game reviews
- Time-series analysis of game popularity trends
- Integration with additional data sources

## License
The code in this project is open source. The dataset belongs to BoardGameGeek, LLC and is used in accordance with their terms of service.
