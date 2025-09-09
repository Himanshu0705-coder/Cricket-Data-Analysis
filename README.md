🏏 IPL Player Performance Comparison Dashboard
This project is a Streamlit web application designed to analyze and visualize the performance of batsmen in the Indian Premier League (IPL). It provides a user-friendly interface to compare multiple players based on various performance metrics.

✨ Features
Multi-Player Comparison: Select and compare the career statistics of two or more batsmen simultaneously.

Comprehensive Career Stats: View key performance indicators such as:

Total Runs Scored

Total Balls Faced

Career Strike Rate

Number of Fours and Sixes

Year-by-Year Analysis: Visualize and compare the players' run totals for each year they have played in the IPL.

Opponent Team Analysis: See a breakdown of how many runs each player has scored against different bowling teams.

Boundary Analysis: Compare the total number of fours and sixes hit by each selected player throughout their career.

Interactive Visualizations: All charts and graphs are created using Plotly, offering a rich, interactive experience.

Data Upload: Users can upload their own CSV file with IPL data, making the app flexible.

📊 Dataset
The application uses a ball-by-ball IPL dataset named ball_by_ball_ipl_data.csv. This dataset contains detailed information for each delivery in an IPL match. The key columns used in this analysis are:

batter_name: The name of the batsman.

batsman_run: Runs scored by the batsman on that ball.

bowling_team: The name of the opposition team.

id: Contains match ID information, which is used to derive the year of the match.

🛠️ Technologies Used
Python: The core programming language.

Streamlit: For building and deploying the interactive web application.

Pandas: For data manipulation and analysis.

Plotly Express: For creating interactive and aesthetically pleasing data visualizations.

🚀 How to Run the Application
To run this application on your local machine, please follow these steps:

Clone the Repository (or Download Files):
Make sure you have IPL.py and ball_by_ball_ipl_data.csv in the same directory.

Install Required Libraries:
Open your terminal or command prompt and install the necessary Python libraries.

pip install streamlit pandas plotly

Run the Streamlit App:
Navigate to the project directory in your terminal and run the following command:

streamlit run IPL.py

View the App:
Streamlit will open a new tab in your web browser with the running application. You can now select players from the sidebar to start the comparison.

📂 File Structure
.
├── IPL.py                     # The main Python script for the Streamlit application
├── ball_by_ball_ipl_data.csv  # The dataset with ball-by-ball IPL data
└── README.md                  # This README file
