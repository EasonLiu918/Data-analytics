# E-commerce Consumer Behavior Data Insights

## 📌 Overview
This project analyzes the **Online Shoppers Intention Dataset** to uncover key behavioral traits and patterns influencing consumer purchase decisions on e-commerce platforms. Through comprehensive preprocessing, visualization, and correlation analysis, we derive insights that can inform business strategies aimed at improving conversion rates and customer engagement.

## 🧰 Tools & Technologies
- **Python 3**, using libraries:
  - `Pandas` for data manipulation and cleaning
  - `Matplotlib` & `Seaborn` for visualizations
  - `NumPy` for numerical computation

## 🗃 Dataset
- **Source**: online_shoppers_intention.csv
- Contains session-level data of user behavior across e-commerce pages
- Binary target variable: `Revenue` (purchase or not)

## 🔍 Exploratory Data Analysis
We examined user activity and purchasing patterns across various dimensions:
- 📅 **Monthly Trends**: Conversion rates and transaction volume peaked around May and November, aligning with seasonal promotions.
- 🔁 **Visitor Types**: New visitors showed higher conversion rates than returning users.
- 💻 **Device Usage**: Operating systems and browsers had varying impacts on user behavior and revenue likelihood.
- 📊 **Session Metrics**: Page values and exit/bounce rates were strong indicators of purchasing behavior.

## 🔗 Correlation Insights
- Top features positively correlated with `Revenue`:  
  `PageValues`, `ProductRelated`, `ProductRelated_Duration`
- Strongest negative correlations:  
  `ExitRates`, `BounceRates`
- Pairplot analysis reveals linear relationships and potential predictors.

## 💡 Key Takeaways
- Tailored strategies for **new vs. returning users** can improve engagement.
- Pages with high `PageValues` deserve strategic prioritization and content optimization.

## 📈 Strategic Recommendations
- Develop **targeted campaigns** during peak months.
- Personalize experiences for **returning visitors** via loyalty programs.
- Reduce friction in **high-exit pages** through A/B testing and UX improvements.
- Align design/interface with top-performing **OS and browsers**.

---

## 📁 Files
- `ISOM_5160_Project.ipynb`: Full analysis and visualization notebook
- `README.md`: Project summary and repository overview

## 👤 Author
Liu Hai-Sung (Eason)  
