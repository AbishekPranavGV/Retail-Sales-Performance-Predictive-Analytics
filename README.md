# Retail-Sales-Performance-Predictive-Analytics

📊 Retail Sales: Turning Data into Demand
Ending the "Inventory Guessing Game" with AI-Driven Analytics

Imagine a retailer losing millions because they have too many winter coats in summer, but no umbrellas when it rains. This project is my solution to that "Inventory Distortion" problem—bridging the gap between messy warehouse data and actual customer demand.
💡 The Problem

In the retail world, being "out of stock" means lost revenue, but "overstocking" means wasted capital. I wanted to build a system that moves beyond simple guesswork to provide a data-driven bridge between warehouse logistics and the consumer.
🛠️ My Approach (The "How")

I didn't just jump into the code. I followed a structured Business Analyst lifecycle:

    Understanding the Goal: I started by authoring BRDs and FRDs to make sure the technical work actually improved KPIs like Turnover Ratio and Sell-through Rate.

    The Heavy Lifting: I built a robust SQL pipeline (using CTEs and Window Functions) to turn "dirty" transactional logs into clean, 7-day and 30-day rolling averages.

    Forecasting the Future: I experimented with ARIMA and Facebook Prophet in Python. I wanted to see which model could better handle the "noise" of retail seasonality and sudden promotions.

    Agile Mindset: I managed this in Sprints, constantly testing the model against real-world scenarios to ensure it didn't just work on my laptop, but would work in a real store.

🚀 The Impact

    No More Guessing: Reached 85%+ forecast accuracy, giving procurement teams a much narrower margin of error.

    Time Reclaimed: I turned a 10-hour-per-week manual reporting nightmare into a real-time Power BI Dashboard that updates instantly.

    The 80/20 Insight: I discovered that just 20% of SKU categories drive 70% of the profit. This allowed us to rethink shelf-space and prioritize high-value inventory.

🧰 Tech Stack
• SQL • Python • ARIMA • Prophet • Power BI • Agile

<img width="1285" height="725" alt="image" src="https://github.com/user-attachments/assets/a0403112-365e-4549-acaf-d7ca41549b0e" />
