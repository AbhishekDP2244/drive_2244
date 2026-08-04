# Delivery Script (Brief) — "Which Model Should I Use?" Cheat Sheet
### ~5–6 minute walkthrough of `AI_Model_Comparison_Cheatsheet_Simple.png`

**Opening:**
"Quick tour of this page — for every model: what it does, when to use it, why pick it, and why you might skip it. Top nine models learn from past examples where we already know the answer. Bottom three just look for hidden groups, with no known answer given."

---

## Group 1 — Learns From Known Answers

- **Linear Regression** — "Draws a straight trend line to predict a number. Use it for simple, steady trends like sales vs. ad spend. Fast and easy to explain, but misleading if the trend isn't a straight line."
- **Logistic Regression** — "Gives a yes/no answer with a confidence %, like churn risk. Simple and fast, but struggles when the real reasons are tangled together."
- **Decision Tree** — "Makes a call using a flowchart of yes/no questions. Great when you need to show the exact rule. Downside: a little unstable — small data changes can reshape it."
- **Random Forest** — "Hundreds of decision trees voting together. Reliable, low-fuss accuracy — but harder to explain any single decision."
- **SVM** — "Draws the clearest line between two groups. Good with lots of factors and clean separation; gets slow on very large data."
- **Naive Bayes** — "Sorts things — like reviews — into categories, fast. Great for text, even with little data; weaker when factors influence each other."
- **KNN** — "Looks at the most similar past examples to decide. Simple, no training needed; slows down as data grows."
- **AdaBoost** — "Chains simple rules, each fixing the last one's mistakes. Steadily improves; a few bad data points can throw it off."
- **XGBoost** — "A powered-up version of that same chaining idea. Usually the most accurate option here — but needs a specialist to set up well."

---

## Group 2 — Finds Hidden Groups, No Known Answer

- **K-Means** — "Splits data into a set number of neat groups. Fast and simple; you must guess the group count upfront."
- **DBSCAN** — "Finds natural clusters and flags the odd ones out automatically. Great for catching outliers; sensitive to its settings."
- **Hierarchical Clustering** — "Builds a family-tree of groups, small to big. Great visual for stakeholders; gets slow on large datasets."

---

## Cheat Codes (say fast, one line each)

- "Predicting a number? Linear Regression. Predicting yes/no? Logistic Regression."
- "Need to show the exact rule? Decision Tree. Want a solid all-rounder? Random Forest. Want the top accuracy? XGBoost."
- "Many factors, clear groups? SVM. Care about similar past cases? KNN. Sorting text fast? Naive Bayes."
- "Know your group count? K-Means. Don't know it, want outliers caught? DBSCAN. Want to explore visually? Hierarchical."
- "Know the answer already? Use the top nine. Don't know it, just exploring? Use the bottom three."

---

**Closing:**
"Keep this page handy — next time someone names a model in a meeting, you'll know what it does, whether it fits, and what to suggest instead if it doesn't."
