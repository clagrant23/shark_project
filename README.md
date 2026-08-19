Climate & Shark Incident Analysis
Overview

Are increasing shark incidents primarily associated with changing ocean conditions, or could increasing human exposure help explain the trend?

This project explores historical shark incident data alongside sea-surface temperature, global temperature anomalies, and Florida population estimates to investigate relationships between environmental change, human exposure, and reported shark incidents.

The goal is not to claim that climate change or population growth directly causes shark incidents, but to use exploratory data analysis to better understand the trends and potential factors behind them.

Research Questions

This analysis focuses on several questions:

How have reported shark incidents changed over time?
How have global and ocean temperatures changed over the same period?
Do shark incident trends appear to move alongside temperature trends?
How does the trend change when Florida incidents are adjusted for population growth?
What can these relationships tell us — and what can they not tell us — about potential drivers of shark incidents?
Data

The project combines multiple datasets covering:

Historical shark incidents
Sea-surface temperature
Global temperature anomalies
Florida population estimates

The datasets are cleaned and combined in Python to compare long-term trends across environmental and human-exposure variables.

Methods

The analysis was completed primarily in Python using Jupyter Notebook.

Key steps included:

Cleaning and filtering historical shark incident records.
Aggregating incidents by year and geographic area.
Processing historical temperature data.
Comparing incident trends with temperature trends.
Normalizing Florida shark incidents using population estimates.
Using rolling averages to make long-term patterns easier to interpret.
Visualizing relationships among incidents, temperature, and population-adjusted incident rates.
Tools
Python
pandas
NumPy
Matplotlib
Jupyter Notebook
Key Findings

The analysis shows that reported shark incidents have changed substantially over time alongside major changes in both environmental conditions and human populations.

Temperature trends provide useful environmental context, but relationships between temperature and shark incidents should not be interpreted as evidence that rising temperatures directly cause more shark incidents.

Adjusting Florida incidents for population growth also demonstrates why raw incident counts alone can be misleading. Increasing numbers of people living in and visiting coastal environments can increase opportunities for human-shark interactions even when the underlying level of risk does not increase proportionally.

Overall, the project highlights the importance of considering both environmental change and human exposure when interpreting long-term wildlife-interaction data.

Limitations

This is an exploratory analysis rather than a causal study.

Important limitations include:

Historical shark incident reporting may be incomplete or inconsistent.
Population is only an approximation of human exposure to coastal waters.
Tourism, beach attendance, surfing participation, fishing activity, and other forms of ocean use are not directly measured.
Temperature is only one of many environmental variables that could affect shark behavior or distribution.
Correlation between two trends does not demonstrate that one causes the other.

Future work could incorporate more direct measures of coastal activity, additional oceanographic variables, geographic analysis, and statistical modeling.

Repository Structure

climate_shark_analytics/
├── data/          # Datasets used in the analysis
├── notebooks/     # Jupyter notebooks containing the analysis
└── README.md      # Project documentation

Future Improvements

Potential extensions of this project include:

Incorporating beach visitation or tourism data as a better measure of human exposure.
Adding geographic analysis of shark incidents.
Examining additional environmental variables such as ocean currents or marine heatwaves.
Developing statistical models to quantify relationships among environmental conditions, human exposure, and shark incidents.
Creating an interactive dashboard for exploring trends by location and year.

Why This Project

I am interested in applying data science to environmental and conservation problems. This project gave me experience working with messy real-world environmental datasets while also demonstrating how careful analysis can add context to commonly misunderstood relationships between wildlife, people, and environmental change.