# smartrestock-lagos-footwear
Predicting restock timing for a Lagos shoe shop using Machine Learning
# SmartRestock: Predicting the Best Time to Restock a Local Shoe Shop in Lagos

## The Story
I came home from school for the holidays hoping to rest. 
Instead, I found my mum frustrated.

She runs a small shoe shop in Idumota market, Lagos. She had 
just spent a significant amount restocking new shoes, fresh 
inventory, shelves fully loaded. And then almost nobody came. 
But the moment her stock ran out, that's when everyone showed 
up to buy.

She was always one step behind. Restocking when demand was low, 
running out exactly when demand was high.

I had just spent weeks learning data science at the Kujenga 
programme. Sitting there listening to her, I realised this 
is exactly the kind of problem data science can solve.

## The Question
Can we use past sales patterns to predict when customer demand 
Will be highest,so a small Lagos shoe shop owner knows exactly 
When to restock?

More specifically:
- Which days of the week bring the most customers?
- Which part of the month sees the highest sales?
- Can a regression model predict these patterns reliably?

## The Dataset
The dataset was built from real sales records collected from my 
mum's footwear shop in Idumota market, Lagos Island. It covers 
2020–2024 and captures:
- Daily demand and units sold
- Revenue in Naira
- Festive periods (Christmas, Easter, Eid)
- Fuel prices and transportation costs
- Seasonal patterns (Dry vs Rainy season)
- Market days and promotions

## Techniques Used
| Technique | Purpose |
|---|---|
| Linear Regression | Core Kujenga course technique — predict demand from patterns |
| Random Forest | Improved accuracy with non-linear relationships |
| Gradient Boosting | Best performing model — captures complex interactions |

## Key Findings
- **Mondays and Fridays** are the highest demand days in Idumota
- **Late month (days 21–31)** sees the strongest sales surge — driven by salary payments
- **Festive periods** (Christmas, Eid) require 2–2.5× normal stock levels
- **Fuel prices above ₦500/litre** suppress demand by approximately 12%

## Restock Calendar
| When | Action |
|---|---|
| Every Sunday evening | Restock for Monday market surge |
| Every Thursday evening | Restock for Friday market surge |
| Around day 18 each month | Bulk restock for end-of-month salary surge |
| 2 weeks before Christmas / Easter | Order 2.5× normal stock |
| 2 weeks before Eid | Order 2.3× normal stock |
| When fuel exceeds ₦500/litre | Reduce restock by ~12% |

## How to Run
1. Open `Halimat_Amzat_Nigeria_Final_project.ipynb` in Google Colab
2. Run all cells from top to bottom
3. The dataset loads automatically from this repository — no setup needed

## Project Structure
📁 smartrestock-lagos-footwear/

├── 📓 Halimat_Amzat_Nigeria_Final_project.ipynb

├── 📄 README.mds

└── 📊 idumota_footwear_lagos.csv

## Why This Matters
In Nigeria, informal retail accounts for 98% of all retail 
transactions. Millions of traders like my mum make restocking 
decisions every day using nothing but instinct and poor 
inventory timing costs businesses up to 11% of their annual 
revenue.

This project shows that even a small, local dataset combined 
with simple data science techniques can produce actionable, 
real-world results.

## Project Video
Watch the 2-minute project video here -> https://youtu.be/r-Djvdi_0Vo

## Author
**Halimat Amzat** | Nigeria  
Kujenga Africa-Europe Core AI Programme
