🚖 NYC Yellow Taxi Data – Exploratory Data Analysis (EDA)

Understanding NYC’s Taxi Operations Through Data Science

📌 About the Dataset

This project analyzes NYC Yellow Taxi trip data, which includes millions of taxi rides recorded over several months. The dataset provides insights into:
	•	Trip details – Pickup & dropoff times, trip distance, passenger count
	•	Fares & payments – Fare amount, tips, congestion surcharges, payment types
	•	Location-based patterns – Pickup & dropoff locations

The goal? To extract valuable business insights from the data before moving into predictive modeling.

📊 What We Did (EDA Process)

1️⃣ Data Preprocessing
	•	Filtered data to focus on the last 4 months to optimize performance.
	•	Removed unrealistic values and outliers (e.g., extreme fares, negative trip distances).
	•	Created new features like trip speed, fare per mile, and peak hour indicators.

2️⃣ Exploratory Data Analysis (EDA)

We performed deep-dive visualizations to uncover key business insights:

🚦 NYC Taxi Demand by Hour
	•	Peak demand is during evening rush hours (4-8 PM) and morning commute (6-10 AM).
	•	Late-night rides (midnight - 3 AM) see demand from nightlife & airport traffic.

📍 Top Pickup Locations
	•	Some locations dominate taxi pickups, likely business hubs, airports, or nightlife areas.
	•	Fleet distribution can be optimized by focusing on high-demand areas.

💰 Trip Distance vs Fare Amount
	•	Short trips have significantly high per-mile fares due to base fares & surcharges.
	•	Long trips have stable pricing, but some anomalies suggest potential overpricing or toll influence.

🏙️ Impact of Congestion Surcharge
	•	Higher congestion surcharges don’t always mean higher fares, questioning pricing efficiency.
	•	Could indicate a need for better dynamic pricing models.

💳 NYC Taxi Payment Methods
	•	Cash still dominates NYC taxi transactions—surprisingly more than credit cards.
	•	Disputes are rare but exist, highlighting a potential fraud detection use case.

⚡ NYC Taxi Trip Speed Distribution
	•	Most taxis travel below 20 mph, confirming heavy congestion in key areas.
	•	Speed trends can be used to optimize traffic-aware pricing.

💲 Trip Distance vs Fare Per Mile
	•	Short trips are disproportionately expensive, while long trips stabilize in pricing.
	•	Adjusting base fares & distance-based pricing could improve customer satisfaction.

🚀 Key Business Insights
	•	Fleet Optimization: Taxis should be strategically positioned in high-demand areas at the right times.
	•	Dynamic Pricing Strategies: Short trips should have more balanced pricing, and congestion surcharges need optimization.
	•	Customer Behavior Insights: Cash is still dominant, and certain locations are always hotspots, making them prime targets for partnerships & ride incentives.
	•	Anomaly Detection & Fraud Prevention: Dispute transactions & fare outliers need deeper analysis to improve trust in taxi fare pricing.

📌 Next Steps

✅ Build a predictive model to forecast taxi demand based on time & location.
✅ Optimize fare pricing strategies based on insights from the EDA.
✅ Explore real-time data to track citywide taxi movement trends.

📢 Want to contribute or collaborate?

Feel free to fork this repo, raise issues, or suggest improvements!

📌 EDA is where real insights are found—before we even touch machine learning. 🚀
