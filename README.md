# Hotel Booking Data Analysis: Revenue & Cancellation Insights
Analyzed by Devangna

## 📌 Project Overview
This project focuses on analyzing hotel booking datasets to understand customer behavior and booking patterns. The primary goal was to identify why **20% of bookings are being cancelled** and to provide data-driven recommendations to reduce revenue leakage.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** `Pandas`, `Matplotlib`, `Seaborn`
* **Environment:** Jupyter Notebook / Google Colab

---

## 📊 Visual Analysis & Key Insights

### 1. Channel Dominance
Digital channels (Web and Mobile App) contribute to approximately **90% of total bookings**.
![Bookings](Bookings%20by%20Channel.png)
* **Observation:** Customers strongly prefer direct digital platforms over traditional travel agents.

### 2. Cancellation Behavior
The analysis revealed a consistent **~20% cancellation rate** (1 in 5 bookings) across all channels.
![Cancellation Rate by Channel](images/cancellation_rate.png)
* **Insight:** Since cancellation rates are similar across platforms, the issue is likely rooted in customer behavior or lack of friction in the cancellation process rather than a specific channel bug.

### 3. Seasonality & Pricing
Booking values peak in **February and March**, indicating strong seasonal demand.
![Monthly Trends](images/monthly_trends.png)
* **Observation:** Revenue is currently driven by volume rather than premium pricing, as booking values remain consistent regardless of hotel star ratings.

---

## 💡 Business Recommendations

### 1. Reduce Revenue Leakage
* **Tiered Penalties:** Introduce cancellation fees that increase as the check-in date approaches.
* **Incentives:** Promote non-refundable, prepaid bookings with price incentives to secure commitment.

### 2. Optimize Channel Strategy
* **Digital Focus:** Reallocate marketing budget toward Web and Mobile channels for better scalability.
* **Conversion Quality:** Implement "urgency nudges" (e.g., "Only 2 rooms left") to improve high-intent bookings.

### 3. Leverage Seasonality
* **Dynamic Pricing:** Increase pricing during peak demand (Feb-March) and launch promotions during low-demand periods (May-June).

---

## 📂 How to Use
1. Clone the repo: `git clone https://github.com/your-username/your-repo-name.git`
2. Install requirements: `pip install pandas matplotlib seaborn`
3. Run the notebook: `jupyter notebook TravClan_Analysis.ipynb`
