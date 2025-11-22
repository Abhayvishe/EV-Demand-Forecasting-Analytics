EV Demand Analysis Dashboard
📊 Project Overview

This project is an analytics dashboard built to analyze and visualize electric vehicle (EV) demand across India. It brings together geographic, temporal, and segment-level data to enable stakeholders — OEMs, policymakers, investors — to make data-driven decisions about EV adoption, infrastructure, and market strategies.

✨ Key Features

Geo Heatmaps: Visualizes EV demand intensity at the state and city level

Segment Breakdown: Compares demand across 2-wheelers, 3-wheelers, 4-wheelers, and commercial EVs

Trend Analysis: Monthly, quarterly, and annual demand patterns to capture seasonality and growth

Policy Impact: Analyzes how government subsidies, incentives, and regulatory changes affect demand

Charging Infrastructure Correlation: Maps EV demand with density and distribution of charging stations

KPI Tracking: Adoption rate, YoY growth, CAGR, conversion funnel metrics

🚀 Why This Matters

Strategic Planning: Helps manufacturers and distributors pinpoint high-opportunity markets

Investment Decisions: Equips investors with clear demand indicators and growth trajectories

Policy Design: Allows government bodies to quantify the effects of incentives and infrastructure rollout

Scalability: Modular design makes it easy to extend with new data sources or dashboards

🧪 Getting Started

These steps will help you run the dashboard locally:

Clone the repository

git clone https://github.com/Abhayvishe/EV-DEMAND-ANALYSIS.git


Navigate to the project folder

cd EV-DEMAND-ANALYSIS


Install dependencies
(Assuming a Python + Dash / Streamlit / whatever stack — adjust as required)

pip install -r requirements.txt


Run the dashboard

python app.py   # or your run command


Open your browser
Navigate to http://localhost:8050 (or the port you’ve configured) to see the dashboard.

📁 Data Sources

EV registration data: [specify if public / private / scraped]

Charging station locations: [source]

Policy data: [source]

Other relevant external datasets: [sources]

(Add descriptions for each dataset — where it’s from, how frequently it’s updated, and how you processed it.)

🔧 Architecture & Technology Stack

Backend: Python, Pandas, NumPy

Visualization: Plotly / Dash (or Streamlit / Power BI / etc.)

Deployment: (Local / Cloud — mention if you’ve deployed to Heroku, AWS, etc.)

Data Storage: CSV / Database / API (mention what you’re using)

📈 Insights & Business Impact

Identification of EV demand hotspots for targeted infrastructure expansion

Quantitative basis for policy evaluation (how incentives drive EV uptake)

Forecasting future demand to guide production planning and supply chain decisions

Highlighting charging network gaps aligned to high-demand zones

🧭 Future Roadmap

Integrate real-time EV registration data for live updates

Add predictive forecasting module using machine learning

Build a mobile-responsive version of the dashboard

Incorporate user feedback mechanisms to refine visualizations and KPIs

Expand to other geographies (outside India) for a global demand view

🤝 Contribution Guidelines

Feel free to contribute:

Fork the repository

Create a new feature branch

Commit your changes with clear messages

Submit a Pull Request

Reviewers will provide feedback, and once approved, your contribution can be merged

📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

🔗 Contact

Maintainer: Abhay Vishe

Email / LinkedIn / Twitter: [If you wish to provide]
