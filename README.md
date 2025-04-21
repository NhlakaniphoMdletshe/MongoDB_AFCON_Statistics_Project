# 🏆 MongoDB_AFCON_Statistics
## 🗂️Data
- teams.js
- players.js
- matches.js
- scores.js
- statistics.js

# 📘 Introduction
- This MongoDB project was developed using data inspired by the Africa Cup of Nations (AFCON) 2023, simulating how data can be stored, managed, and analyzed using MongoDB.
- The project includes five collections — teams, players, matches, scores, and statistics — to reflect real-world tournament data, including team performance, match results, 
and player stats. It's designed to showcase how MongoDB can structure sports data in a flexible, document-based database system.

## 🌍 Dataset Theme: AFCON 2023
- The dataset reflects elements of the 2023 AFCON tournament, including:
- 🏟️ Teams: Participating countries in AFCON 2023
- 👤 Players: Squad members with positions and nationality
- 📅 Matches: Fixtures between teams, dates, and outcomes
- 📊 Scores: Final scores for each match
- 📉 Statistics: Individual player performance metrics

# 🔍 Mongo Shell Query Examples
## 1. 🗃️ Basic Commands
- These commands help you get started with MongoDB.
Use AFCON_Football_Statistics_Database switches to the database named AFCON_Football_Statistics_Database.
show collections lists all the data tables (called collections) inside that database.

![collections1](https://github.com/user-attachments/assets/99af117e-7ac0-493c-b8c8-4494834fa123)

## 2. 📄 Fetching all Documents
- These commands show all the data inside specific collections.
db.teams.find() fetches all documents from the teams collection and makes them easier to read.
db.players.find() does the same for the players collection.

![fecthing documents2](https://github.com/user-attachments/assets/175f16b9-1782-4662-a20e-91d19f105e2a)

![fecthing documents22](https://github.com/user-attachments/assets/9b5c38a5-94b2-45e1-b414-bb7fb9418dec)

## 3. 🧮 Count Documents
- This command tells you how many records are in a collection.
db.statistics.countDocuments() counts all the documents in the statistics collection.

![Counting Players4](https://github.com/user-attachments/assets/9c33eb57-d163-4639-b6d6-0f55cb40e082)

## 5. 📊 Aggregation
- This command helps you find the top players who scored the most goals.
- 
![aggregation5](https://github.com/user-attachments/assets/a8691700-f247-4f0b-b174-fad484f81678)

## What it does:
- Groups the data by player name ($player)
- Adds up all the goals for each player ($sum)
- Sorts them from highest to lowest ($sort)
- Shows only the top 5 goal scorers ($limit)
- This is useful for quickly identifying the top performers in the tournament!

## 💡 Insights Gained
- Demonstrated how real tournament data (AFCON 2023) can be organized into NoSQL collections.
- Aggregation pipelines allow deep insight into player performance.
- MongoDB provides an excellent structure for flexible, non-relational sports data analytics.

# 📌 Conclusion
- This project serves as a real-world simulation of how to use MongoDB to manage sports tournament data, specifically based on AFCON 2023. 
It offers a practical guide for developers or data analysts interested in building sports data systems using MongoDB.







