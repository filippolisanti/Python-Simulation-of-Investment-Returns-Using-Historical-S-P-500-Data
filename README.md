# Simulation-of-Investment-Returns-Using-Historical-S-P-500-Data
**Created while working as a portfolio management intern at C-Quadrat, a European Hedge Fund and Investment Group.**

This Python script is designed to simulate the potential outcomes of an investment in the S&P 500 over a specified number of years based on historical return data from 1926 to 2023. The script performs three different types of simulations to estimate future investment outcomes using historical annual return rates:

1. **Real Interval Simulation**: This method simulates investment outcomes by randomly selecting consecutive historical return periods matching the user-specified duration of investment (e.g., 20 years). This approach provides insights into how a lump-sum investment would have performed during actual historical periods.

2. **Combined Interval Simulation**: This simulation method constructs synthetic investment periods by randomly selecting two separate 10-year intervals and combining them to simulate a 20-year investment period. This method helps assess the variability in investment outcomes by mixing different historical periods.

3. **Random Interval Simulation**: Unlike the other two simulations that use consecutive years, this method randomly selects any years within the entire dataset to fill the investment duration. This approach tests the investment outcomes in completely randomized scenarios, disregarding the chronological order of returns.

Each simulation runs a million trials to generate a robust dataset of possible outcomes. The script then calculates and displays statistics for each simulation, including the minimum, average, and maximum returns, and the probability of the investment's final amount being below the initial investment or a target value adjusted for a 3% annual inflation rate.

This analysis offers insights into the risks and rewards associated with different investment durations and strategies, aiding investors in making informed decisions based on historical performance.
