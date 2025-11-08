# 🗳️ Lok Sabha Election 2024 Results Analysis | SQL & Power BI

This project presents a **comprehensive analysis** of the **2024 Lok Sabha (Indian General) Election** using **SQL** and **Power BI**.  
By transforming raw voting data into meaningful insights, the project uncovers **patterns in vote shares, party performance, and constituency-level results** across India.

---

## 📌 Project Overview

The **Lok Sabha Election 2024 Results Analysis** project leverages **SQL queries** and **Power BI dashboards** to understand India's democratic outcomes.  
The dataset includes details on states, constituencies, candidates, political parties, vote counts, and winning margins.

### 🔍 Focus Areas
- Party-wise seat distribution  
- Vote share analysis  
- Constituency-level comparisons  
- Margin of victory and competition  
- EVM vs Postal vote trends  

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|----------|
| 🧮 **SQL Server** | Querying, aggregation, and KPI extraction |
| 📊 **Power BI** | Data visualization and dashboarding |
| 📑 **Excel** | Raw dataset storage and preprocessing |

---

## 📂 Dataset Description

The dataset contains **row-level data** for each candidate contesting in every constituency for the **2024 Indian General Elections**.

| Column Name | Description |
|--------------|-------------|
| `election_year` | Year of the election (2024) |
| `state_name` | Name of the state |
| `constituency_name` | Name of the constituency |
| `constituency_type` | General or Reserved (e.g., ST, SC) |
| `party_name` | Name of the political party |
| `candidate_name` | Name of the contesting candidate |
| `EVM_votes` | Votes received through Electronic Voting Machines |
| `postal_votes` | Votes received via postal ballots |
| `total_votes` | Combined total votes (EVM + postal) |
| `rank` | Rank based on total votes in the constituency |
| `units` | Indicates absolute vote counts |

---

## ❓ Key Questions Answered

- Which party secured the highest number of seats?  
- What is the distribution of votes by party and state?  
- Which candidates had the highest winning margins?  
- How many total votes were cast through EVM and postal ballots?  
- Which constituencies had the closest races?  
- What percentage of seats were won by top political parties?  
- How many independent candidates contested, and how did they perform?  

---

## 🔍 Key Insights

- 🧭 **Bharatiya Janata Party (BJP)** secured the majority with **239 seats**.  
- 🏛️ **Indian National Congress (INC)** followed with **99 seats**.  
- 📊 **645 million total votes** were recorded — **99.42% via EVMs**.  
- ⚖️ Close contests observed in multiple constituencies (margins under 1,000 votes).  
- 🗳️ Several constituencies had **10+ candidates**, showing strong competition.  
- 🚨 **NOTA** received **6 million+ votes**, indicating rising voter awareness.  

---

## 📊 Power BI Dashboard Features

- Top 5 Parties by Seats & Vote Share  
- State-wise Constituency Votes (Map Visualization)  
- EVM vs Postal Votes Overview  
- Victory Margins by Candidate  
- Interactive Filters by State & Constituency  
- Party-wise Constituency Table  

> 📍 *Dashboard screenshots and SQL queries can be found in the respective folders.*

