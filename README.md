# Power-BI-Dashboards

Project Objective
The goal of this project was to examine the relationship between music listening behavior and markers of mental health using interactive visual analytics in Power BI.
We sought to reveal patterns of how genre liking, frequency of listening, and streaming services are related to levels of anxiety, depression, insomnia, and OCD.

Dataset Used
Name: mxmh_survey_results.csv
Total Rows: 736
Columns: 33

Key Column Categories:
Demographics: Age, Foreign languages, Instrumentalist, Composer

Music Habits: Primary streaming service, Hours per day, Fav genre, 15+ Frequency [Genre] columns

Mental Health Scores: Anxiety, Depression, Insomnia, OCD

Behavioral Tags: While working, Music effects, Exploratory

⚠️ Missing Data:
BPM had ~107 missing values

Small nulls in Music effects, Instrumentalist, Age, etc.

Data was cleaned using Power Query in Power BI

 Page 1: Overview – Listening Behavior & Mental Health
🎯 Focus:
General listening trends and overall mental health scores

📈 Visuals Created:
KPI Cards:

Avg Listening Time: 3.57 hrs/day

Avg Anxiety Score: 5.84

Donut Chart: Most used streaming platforms (Spotify dominates with 62%)

Bar Chart: Top Favorite Genres (Rock, Pop, Metal)

Stacked Column Chart: Genre preferences split by ListeningCategory (Low/Med/High)

🧠 Insights:
Rock and Pop dominate across all listeners

High-frequency listeners prefer more emotionally charged genres like Metal

Streaming platforms like Spotify and YouTube Music are preferred by emotionally active users

Page 2: Genre Frequency vs Mental Health
🎯 Focus:
Explore how specific genres relate to mental health conditions

📈 Visuals Created:
Scatter Plot: Correlation between Anxiety and Depression

Grouped Bar Charts:

Frequency [Rock] & Frequency [Pop] by Anxiety Group

Stacked Column Chart:

Sum of Mental Health Scores by Genre

Combined Bar+Line Chart:

Count of “Music Effects” + Avg Listening Time by Age and Genre

Genre Filter Panel: Interact with visuals by selecting specific genres

🧠 Insights:
Teens and 20s report the highest music emotional effects

High-frequency Rock and Pop listeners tend to show higher anxiety

Classical and Gospel genres show lower emotional volatility

Page 3: User Deep Dive & Segment Profiles
🎯 Focus:
Examine individual-level behavior and allow drillthrough for detailed exploration

📈 Visuals Created:
User Data Table: Age, Hours, Anxiety, Depression, Insomnia

Bar Chart: Avg Listening Hours by Age Group (Teens listen the most)

Grouped Bar Chart:

Streaming platform & genre usage split by Anxiety Group

Stacked Column Chart:

Avg Mental Health Score (Anxiety, Depression, Insomnia) by Genre

100% Stacked Bar:

Proportion of Low/High Anxiety across genre listeners

🧠 Insights:
Teens listen to the most music and report strong emotional effects

Even high-anxiety users prefer Spotify and other popular platforms

Mental health score profiles differ clearly by genre

 #Final Key Insights:
Music is a strong emotional regulator – users with higher mental health scores listen more often.

Genre matters – Rock, Pop, and Metal are most associated with high emotional impact.

Age is a big factor – Teens and 20s are the most emotionally influenced by music.

Listening platforms show patterns – High anxiety users still prefer mainstream services.

Data-driven storytelling allows meaningful mental health awareness using music data.
