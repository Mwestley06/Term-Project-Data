Game Stats Manager

The Game Stats Manager project organizes and analyzes basketball player performance data across multiple games. The dataset includes 60 rows of realistic game statistics for five players on the Sharks team. Each row represents a player's performance in a specific match.

 Project Structure

- Data-Files/
- GameStatsData.xlsx
- tables.sql
- ERDiagram.txt
- ProjectExplanation.txt

 Dataset Columns

The Excel file contains the following columns:

- PlayerName
- PlayerID
- Team
- MatchDate
- Opponent
- PointsScored
- Assists
- Rebounds
- Result

These fields represent player performance for each match.

 ER Diagram Overview

Entities
- Player
- Team
- Match
- Stats

### Relationships
- A team has many players
- A team has many matches
- A player has many stats entries
- A match has many stats entries

### ER Diagram Structure (Text Version)

Player (PlayerID, PlayerName, TeamID)
Team (TeamID, TeamName)
Match (MatchID, MatchDate, Opponent, Result, TeamID)
Stats (StatID, PlayerID, MatchID, PointsScored, Assists, Rebounds)

 SQL Tables

The project includes four SQL tables:

- Team
- Player
- Match
- Stats

These tables store team information, player details, match records, and individual player statistics.

 Purpose of the Project

This project demonstrates:

- Creating and organizing a dataset
- Designing an ER diagram
- Building relational SQL tables
- Modeling real-world sports data
- Understanding relationships between entities

It shows how player performance data can be structured, stored, and analyzed using database concepts.
