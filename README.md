# Weather Impact on Flight Delays

End-to-end analysis of how weather conditions (precipitation, temperature, wind speed) affect U.S. domestic flight delays, using SQL, statistical hypothesis testing, and an interactive Power BI dashboard.

## Business Case
Airlines lose significant revenue and customer trust due to flight delays. This analysis quantifies weather's real impact on delays using real flight and weather data, and tests whether the relationship is statistically significant or just commonly assumed.

## Dataset
Source: Historical Flight Delay and Weather Data (Kaggle)
Time Period Analyzed: May - July 2019
Size: 2,058,732 clean flight records

## Key Findings
- Precipitation is the strongest delay driver: 30.89 min avg delay vs 8.39 min with no precipitation (p < 0.001)
- Wind speed shows a clear trend: 9.05 min (low wind) to 15.88 min (high wind)
- Temperature has a statistically significant but practically minor effect (under 2 min difference)
- June had the worst delays (12.89 min avg), coinciding with highest precipitation

## Tools Used
Python, Pandas, SQLite, SciPy, Matplotlib, Power BI
