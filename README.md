🏏 IPL 2022 Data Analysis – My Capstone Project
📌 About the Project

This is my capstone project where I did an exploratory data analysis (EDA) on the IPL 2022 season. IPL is one of the biggest T20 cricket leagues in the world, and I wanted to dig into the data and pull out some real insights — team performance, toss trends, top scorers, best bowlers, venues, everything.

I used Python along with Pandas, NumPy, Seaborn, and Matplotlib to do the analysis.

The dataset I worked with has 74 matches from IPL 2022 and 20 columns covering match details, teams, scores, winners, Player of the Match, top scorers, and bowling figures.

🎯 What I Wanted to Find Out
Which teams won the most matches, and how their win % compares
Toss trends — who won tosses, what decisions they made, and whether winning the toss actually helped win the match
Who the top-performing batsmen were
Who bagged the most Player of the Match awards
Which bowlers stood out
How matches were won — by runs or by wickets, and by how much
Which venues hosted the most games
Turning all of this into clear visualizations
📊 Dataset

74 matches, 20 columns:

Column	Description
match_id	Unique match identifier
date	Match date
venue	Match venue
team1	First team
team2	Second team
stage	Tournament stage
toss_winner	Team that won the toss
toss_decision	Decision after winning the toss
first_ings_score	First innings score
first_ings_wkts	Wickets lost in first innings
second_ings_score	Second innings score
second_ings_wkts	Wickets lost in second innings
match_winner	Winning team
won_by	Won by runs or wickets
margin	Winning margin
player_of_the_match	Player of the Match
top_scorer	Top scorer of the match
highscore	Top scorer's score
best_bowling	Best bowler of the match
best_bowling_figure	Best bowling figures

Before jumping into analysis, I checked the shape of the dataset, the data types, and made sure there were no missing values — all 74 rows had values across all 20 columns.

🛠️ Tools I Used
Python
Jupyter Notebook
Pandas – for data manipulation
NumPy – for numerical operations
Matplotlib – for plotting
Seaborn – for statistical visualizations
🔍 What I Did, Step by Step

1. Basic Data Exploration Loaded the dataset, checked the first few rows, looked at the shape, column names, data types, and confirmed there were no missing values.

2. Team Performance Worked out matches played, matches won, and win percentage for each team to see who dominated the season.

3. Toss Analysis Looked at which teams won the most tosses, what they chose to do after winning (bat/field), and whether winning the toss actually translated into winning the match.

4. Batting Performance Analyzed the top_scorer and highscore columns to find who scored the most cumulative match-high-scores across the season.

5. Player of the Match Counted up who received the most POTM awards.

6. Bowling Performance Looked at the best bowler in each match, their figures, and how often they showed up as the standout performer.

7. Venue Analysis Checked which stadiums hosted the most matches.

8. Match-Winning Margins Broke down matches won by runs vs. wickets, and found the biggest winning margins of the season.

📈 Visualizations

I used Matplotlib and Seaborn to visualize all of this — win counts, toss trends, top scorers, POTM awards, venue distribution, and winning margins — to make the insights easier to read at a glance.

💡 Key Insights I Found
🏆 Gujarat Titans had the most wins in the season — 12 wins
🥇 Rajasthan Royals came in second with 10 wins
📊 Lucknow Super Giants and Royal Challengers Bangalore each had 9 wins
🏏 Jos Buttler led the match-level high-score analysis with 651 cumulative runs, followed by Quinton de Kock with 377 (Note: this 651 is based on my match-level dataset calculation, not the official IPL season aggregate of 863 runs — just flagging that difference.)
⭐ Kuldeep Yadav picked up the most Player of the Match awards — 4
🪙 Gujarat and Hyderabad won the most tosses, 10 each
📍 Wankhede Stadium, Mumbai hosted the highest number of matches
📁 Project Structure
IPL_2022_Analysis/
│
├── IPL 2022_Capstone_project.ipynb
├── IPL.csv
└── README.md
🚀 How to Run This Project
Clone the repo
   git clone https://github.com/mo-anas561/IPL_2022_Analysis.git
Move into the project folder
   cd IPL_2022_Analysis
Install the required libraries
   pip install pandas numpy matplotlib seaborn jupyter
Launch Jupyter Notebook
   jupyter notebook
Open IPL 2022_Capstone_project.ipynb

Make sure IPL.csv is in the same folder as the notebook before running it.

📚 What I Learned From This Project

This project really helped me get hands-on with:

Exploratory Data Analysis (EDA)
Data cleaning and preprocessing
Working with Pandas DataFrames
GroupBy operations and aggregation
Filtering and sorting data
Basic statistical analysis
Data visualization with Matplotlib/Seaborn
Pulling business-style insights out of a real dataset
Presenting findings in a clear, readable way
🔗 Notebook

Full analysis and visualizations here: IPL 2022 Capstone Project Notebook

👨‍💻 Author

Mo Anas GitHub: @mo-anas561

⭐ Support

If you found this project useful, drop a ⭐ on the repo!
