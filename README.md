# ⚽ Arsenal Match Analysis with Matplotlib

##  Project Overview
This project presents a **data-driven analysis of Arsenal FC’s match performances** using **Python, Pandas, and Matplotlib**.  
It explores the club’s results through visual storytelling — highlighting **coaching performance, referee influence, and defensive patterns** against strong opponents.

Each visualization is designed to communicate insights that go beyond numbers, showing how management and match conditions shape Arsenal’s outcomes.

---

##  Objectives
- Analyze Arsenal’s **win rate under different coaches**.  
- Examine **referee patterns** and their relationship with Arsenal’s results.  
- Identify **opponents that consistently score most** against Arsenal.

---

## 📂 Dataset Description
The dataset `matches.csv` contains detailed records of Arsenal matches across multiple seasons.

| Column | Description |
|---------|-------------|
| `Season` | Football season (e.g., 2017/18). |
| `Date` | Match date. |
| `Opponent` | Opponent team. |
| `HoAw` | Match location — home or away. |
| `ArsenalScore` | Goals scored by Arsenal. |
| `OpponentScore` | Goals scored by opponent. |
| `Stadium` | Venue of the match. |
| `Attendance` | Crowd attendance. |
| `Coach` | Arsenal’s coach for the match. |
| `Referee` | Referee in charge of the match. |

---

## 📊 Key Visualizations and Insights

### 1. Arsenal’s Win Rate by Coach
Compares the win percentage achieved by each Arsenal manager.  
**Insight:** Shows which coach delivered the strongest consistency and results over time.

### 2️. Referee Influence on Arsenal Wins
Evaluates how match outcomes vary under different referees.  
**Insight:** Identifies referees associated with higher or lower win rates — useful for pattern recognition or bias analysis.

### 3️. Teams That Score Most Against Arsenal
Ranks opponents by their average goals per match against Arsenal.  
**Insight:** Reveals defensive weak spots and identifies the toughest teams Arsenal faces.

---

##  Analytical Highlights
- Managerial performance has a **visible impact** on team results.  
- Some referees appear more often in Arsenal wins than others.  
- Opponents such as **Liverpool or Manchester City** typically score more goals, indicating consistent defensive pressure.

---

##  Tools and Libraries
- **Python 3.11+**  
- **Pandas** – data manipulation and analysis  
- **Matplotlib** – visualization and styling  
- **Seaborn** – optional for enhanced visuals  

---

##  How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/arsenal-analysis.git
