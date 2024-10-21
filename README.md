Pitch Recognition and Sequencing Analysis for MLB Athletes
Overview
This project explores pitch recognition and sequencing analysis using MLB data. The goal is to uncover patterns in pitch sequences and their outcomes, which can help athletes and coaches better understand how pitchers operate and how different pitch sequences affect at-bat results. The insights can be applied to virtual reality-based training systems like those used by WIN Reality, enhancing a player's pitch recognition and in-game decision-making.

Project Components
Exploratory Data Analysis (EDA):

Initial exploration of MLB data, including distribution of pitch types, pitch speeds, and outcomes (balls, strikes, hits, etc.).
Key visualizations include:
Pitch type distribution
Speed distribution
Location-based heatmaps
Pitch outcome distribution across different pitch types
Pitch Sequence Analysis:

Analysis of top pitch sequences (e.g., fastball to slider) and their corresponding outcomes.
Visualizations to show how pitch sequences impact results like hits, swinging strikes, and fouls.
Distribution of pitch sequences by count (0-0, 1-0, etc.), inning, and baserunner states.
Game Situation Insights:

Visualization of pitch type usage by:
Ball-strike count
Inning
Number of outs
Baserunner combinations
Focus on understanding how game situations influence pitch selection and effectiveness.
Technologies Used
Python (Google Colab for notebook analysis):
Pandas: Data manipulation and cleaning
Pybaseball: Access to MLB pitch data
Matplotlib/Seaborn: Data visualizations
Numpy: Numerical operations
Data Visualization:
Initial project used Tableau for creating interactive visualizations (later shifted back to Python-based visualizations for ease of sharing).
Dataset
The project uses MLB Statcast data accessed via the pybaseball Python library. Data includes:

Pitch types (fastball, slider, etc.)
Pitch speed, location, and spin
Game situations (balls, strikes, baserunners)
Outcome data (ball, strike, hit, etc.)
Installation & Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-repo/pitch-sequencing-analysis.git
Install required Python libraries:

bash
Copy code
pip install pandas numpy pybaseball matplotlib seaborn
Download the dataset using the pybaseball library (if not using the provided dataset):

python
Copy code
from pybaseball import statcast
data = statcast('2024-04-01', '2024-09-30')
Load the project in Google Colab or Jupyter Notebook for interactive exploration:

bash
Copy code
jupyter notebook Pitch_Sequencing_Analysis.ipynb
Usage
Run the provided Jupyter notebook to explore:

The top 10 pitch sequences and their outcomes
Game situation analysis with different pitch types and sequences
Visualizations showing the effectiveness of different pitch sequences in various game contexts.
Project Goals
Help athletes and coaches understand how different pitch sequences affect game outcomes.
Create a presentation for WIN Reality to showcase how this analysis can be used in their virtual reality training system, improving pitch recognition and decision-making.
Expand the analysis to cover more granular game situations (counts, outs, innings, and baserunner states).
Future Work
Incorporating WAR (Wins Above Replacement) to analyze how top pitchers use pitch sequences.
Expanding visualizations to cover multi-pitch sequences.
Applying machine learning to predict pitch outcomes based on sequences and game situations.
Acknowledgments
This project was created as part of a job application for WIN Reality and aims to demonstrate proficiency in data analysis, sports analytics, and visualizations.

Special thanks to ChatGPT for assistance in brainstorming ideas, debugging code, and refining the project's structure and analysis.

