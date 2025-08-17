🏨 Hostel Pricing Analysis – Data Analytics Internship Assignment

This project analyzes hostel pricing patterns for goSTOPS using booking data. The goal is to uncover how factors like advance booking, weekdays vs weekends, seasonal trends, and location differences affect hostel prices, and to provide data-driven pricing recommendations.

## 📂 Project Structure  

.
├── Assignment.ipynb # Jupyter Notebook with data cleaning, analysis & plots
├── DA assignment data.csv # Dataset provided for the assignment
├── Data Analytics Internship Assignment.pdf # Assignment instructions
├── Hostel_Pricing_Analysis.docx # Final report with insights, charts, and recommendations
└── README.md # Project overview (this file)


## 📂 Project Structure  

.
├── Assignment.ipynb # Jupyter Notebook with data cleaning, analysis & plots
├── DA assignment data.csv # Dataset provided for the assignment
├── Data Analytics Internship Assignment.pdf # Assignment instructions
├── Hostel_Pricing_Analysis.docx # Final report with insights, charts, and recommendations
└── README.md # Project overview (this file)

⚙️ Tools & Libraries

Python (pandas, numpy, matplotlib, seaborn)

Jupyter Notebook for analysis

Matplotlib for visualizations

python-docx for creating the final report

📊 Analysis Overview
1. Advance Booking vs Pricing

Last-minute bookings (0 days) are the most expensive.

Prices drop significantly for bookings 8–30 days in advance.

Private rooms are always priced higher than dorms.

2. Weekly Patterns

Saturdays have the highest average prices, followed by Sundays.

Weekend bookings are more expensive than weekday bookings.

3. Seasonal Trends

Peak months: December, November, March

Low season: July (lowest average prices)

Price variation across months is ~40%.

4. Location-Based Differences

Different cities show different advance booking effects.

In City 24, hostels follow similar seasonal patterns (correlations ~0.9+).

5. Pricing Recommendations

Apply last-minute premium pricing for 0-day bookings.

Offer discounts during low-season months (June–August).

Example rule: If 0-day booking price > 10% higher than 8–30 day booking price, add 10–15% premium for private rooms.

📌 How to Run

Clone the repo / download files.

Open Assignment.ipynb in Jupyter Notebook.

Run all cells to:

Clean the dataset

Generate visualizations

Perform correlation analysis

Final results are summarized in Hostel_Pricing_Analysis.docx.

🧑‍💻 Author

Uday Kumar
(Data Analytics Enthusiast | Python, SQL, Power BI, ML)
