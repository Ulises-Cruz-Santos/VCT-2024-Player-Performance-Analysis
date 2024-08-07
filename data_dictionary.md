# Data Dictionary for Valorant Champions Tour 2024 Player Performance Dataset

This document provides a detailed description of the variables included in the Valorant Champions Tour 2024 player performance dataset.

## Basic Information

| Variable Name     | Description                                      | Data Type |
|-------------------|--------------------------------------------------|-----------|
| `Event`           | Name of the event                                | String    |
| `Player`          | Name of the player                               | String    |
| `Team Abbreviated`| Abbreviated name of the team                     | String    |
| `Team Complete`   | Complete name of the team                        | String    |
| `Rnd`             | Number of rounds played                          | Integer   |

## Overall Performance Metrics

| Variable Name | Description                                      | Data Type |
|---------------|--------------------------------------------------|-----------|
| `R`           | Rating: Overall player rating                    | Float     |
| `ACS`         | Average Combat Score                             | Float     |
| `K:D`         | Kill:Death Ratio                                 | Float     |
| `KAST`        | Kill, Assist, Survive, Trade Percentage          | Float     |

## Damage and Elimination Stats

| Variable Name | Description                                      | Data Type |
|---------------|--------------------------------------------------|-----------|
| `ADR`         | Average Damage per Round                         | Float     |
| `KPR`         | Kills per Round                                  | Float     |
| `APR`         | Assists per Round                                | Float     |
| `FKPR`        | First Kills per Round                            | Float     |
| `FDPR`        | First Deaths per Round                           | Float     |

## Accuracy and Skill Indicators

| Variable Name | Description                                      | Data Type |
|---------------|--------------------------------------------------|-----------|
| `HS%`         | Headshot Percentage                              | Float     |
| `CL%`         | Clutch Success Percentage                        | Float     |
| `CL`          | Clutches Won/Played                              | Integer   |
| `CW`          | Clutches Won                                     | Integer   |
| `CP`          | Clutches Played                                  | Integer   |

## Match Highlights

| Variable Name | Description                                      | Data Type |
|---------------|--------------------------------------------------|-----------|
| `KMax`        | Maximum Kills in a Single Map                    | Integer   |

## Aggregate Statistics

| Variable Name | Description                                      | Data Type |
|---------------|--------------------------------------------------|-----------|
| `K`           | Total Kills                                      | Integer   |
| `D`           | Total Deaths                                     | Integer   |
| `A`           | Total Assists                                    | Integer   |
| `FK`          | Total First Kills                                | Integer   |
| `FD`          | Total First Deaths                               | Integer   |

## Notes
- **Event**: Refers to the specific Valorant Champions Tour event during which the performance metrics were recorded.
- **Player**: The name of the player whose performance is being measured.
- **Team Abbreviated**: A shorthand version of the team name.
- **Team Complete**: The full name of the team.
- **Rounds Played (Rnd)**: The total number of rounds the player participated in during the event.
- **Rating (R)**: A composite score representing the overall performance of the player.
- **Average Combat Score (ACS)**: Average score earned by the player per round based on combat performance.
- **Kill:Death Ratio (K:D)**: Ratio of kills to deaths.
- **Kill, Assist, Survive, Trade Percentage (KAST)**: The percentage of rounds in which the player contributed through kills, assists, surviving, or trading.
- **Average Damage per Round (ADR)**: The average damage dealt by the player per round.
- **Kills per Round (KPR)**: The average number of kills per round.
- **Assists per Round (APR)**: The average number of assists per round.
- **First Kills per Round (FKPR)**: The average number of first kills (the first kill of the round) per round.
- **First Deaths per Round (FDPR)**: The average number of first deaths (the first death of the round) per round.
- **Headshot Percentage (HS%)**: The percentage of kills that were headshots.
- **Clutch Success Percentage (CL%)**: The percentage of clutch attempts (situations where the player is the last one alive on their team) that were successful.
- **Clutches Won/Played (CL)**: The ratio of clutches won to clutches attempted.
- **Clutches Won (CW)**: The total number of clutches won.
- **Clutches Played (CP)**: The total number of clutches attempted.
- **Maximum Kills in a Single Map (KMax)**: The highest number of kills the player achieved in a single map.
- **Total Kills (K)**: The total number of kills achieved by the player.
- **Total Deaths (D)**: The total number of deaths experienced by the player.
- **Total Assists (A)**: The total number of assists provided by the player.
- **Total First Kills (FK)**: The total number of first kills achieved by the player.
- **Total First Deaths (FD)**: The total number of first deaths experienced by the player.

This data dictionary helps in understanding the structure and meaning of the dataset, providing a clear reference for analysis and interpretation.
