# Rajasthan Royals: IPL 2027 Auction War Room Analysis
**SupeRR Selector Season 2 — Round 1: Most Reliable Players Under Pressure**

## 1. Executive Summary & Pressure-Reliability Index (PRI)
Traditional T20 metrics reward flat-track accumulation. To identify true clutch performers for the Rajasthan Royals IPL 2027 Auction using ball-by-ball IPL & T20I data (2022–2026), we engineered the **Pressure-Reliability Index (PRI)**:

* **Batting Pressure Filters:** Chasing with Required Run Rate (RRR) >= 9.0, Death Overs (17–20), or Early Collapse (>= 3 wickets down in overs 1–10). Minimum sample: 50 balls faced.
* **Bowling Pressure Filters:** Bowling in Death Overs (17–20) or defending High-RRR Chases (RRR >= 9.0). Minimum sample: 60 balls bowled.

## 2. Top 10 Batters Under Pressure (PRI Ranked)
| Rank | Batter Name | Pressure Runs | Strike Rate | Boundary % |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Vaibhav Sooryavanshi | 468 | 236.36 | 41.41% |
| 2 | Tim David | 1538 | 190.82 | 27.67% |
| 3 | Suryakumar Yadav | 2011 | 171.73 | 25.79% |
| 4 | Dinesh Karthik | 915 | 189.44 | 28.99% |
| 5 | Nicholas Pooran | 1666 | 165.61 | 23.76% |
| 6 | Jos Buttler | 1388 | 166.03 | 24.76% |
| 7 | Abhishek Sharma | 1101 | 172.30 | 26.76% |
| 8 | Rinku Singh | 1467 | 166.14 | 23.78% |
| 9 | Yashasvi Jaiswal | 942 | 168.52 | 28.80% |
| 10 | Andre Russell | 843 | 178.60 | 27.75% |

## 3. Top 10 Bowlers Under Pressure (PRI Ranked)
| Rank | Bowler Name | Wickets | Economy Rate | Dot Ball % |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Arshdeep Singh | 135 | 9.61 | 35.77% |
| 2 | Jasprit Bumrah | 58 | 7.65 | 39.75% |
| 3 | Rashid Khan | 82 | 7.98 | 33.90% |
| 4 | Mitchell Santner | 49 | 7.38 | 38.40% |
| 5 | Sufiyan Muqeem | 15 | 5.73 | 50.45% |
| 6 | Bhuvneshwar Kumar | 74 | 9.06 | 35.55% |
| 7 | Ravi Bishnoi | 71 | 8.90 | 35.26% |
| 8 | Mohammad Nawaz | 31 | 6.72 | 39.88% |
| 9 | Abrar Ahmed | 22 | 6.15 | 41.67% |
| 10 | Josh Hazlewood | 50 | 9.19 | 40.05% |

## 4. Repository Contents & Dataset (`.zip`)
* **`data.zip` (Dataset Archive):** Due to GitHub file size limits, all raw IPL & T20I datasets (2022–2026) are compressed inside this `.zip` archive. It contains:
  * `ball_by_ball.csv` (Delivery-level tracking data)
  * `matches.csv` (Match metadata, venues, and results)
  * `teams.csv`, `competitions.csv`, `playing_eleven.csv`, and `competition_team_player_mapping.csv`
* **`T20_Performance_Dashboard.xlsx`:** Multi-tab Excel Dashboard featuring tournament KPIs, Top Batters, and Top Bowlers.
* **`SuperR_Selector_Season_2_War_Room_Report.pptx`:** Complete War Room Presentation Deck covering methodology, PRI formulas, and RR squad integration strategy.

## 5. How to Extract & Run
1. Clone or download this repository.
2. Extract the **`data.zip`** file in the root directory so that `ball_by_ball.csv` and `matches.csv` are in the same folder as the analysis script:
   ```bash
   unzip data.zip
