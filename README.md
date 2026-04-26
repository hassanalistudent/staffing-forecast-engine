#  Staffing Forecast Engine

Forecasts expert workload using probabilistic project data. Simulates thousands of scenarios to estimate monthly demand, smooth risk, and guide staffing decisions.

##  Overview

This project models future workload for experts (QA, Mobile, Web, DevOps, UI/UX, PM) based on uncertain project leads. It uses Monte Carlo simulation, weighted averages, and hybrid logic to generate realistic forecasts and help managers make informed staffing decisions.

##  Key Features

- Simulates project activation using probabilistic inputs
- Aggregates expert-level manhours across thousands of scenarios
- Outputs monthly workload distributions with mean, standard deviation, and confidence intervals
- Supports CSV export for dashboard integration
- Modular design for easy scaling and customization

##  How It Works

1. **Input**: Each project has a start date, probability of success, and estimated manhours per expert.
2. **Simulation**: The model randomly activates projects based on their probabilities and calculates workload.
3. **Repetition**: Runs thousands of simulations to capture variability and risk.
4. **Output**: Generates monthly workload summaries per expert, ready for visualization or reporting.

##  Files Included

- `Simulation.ipynb`: Core simulation logic and analysis
- `expert_monthly_allocation.csv`: Sample output for dashboard use
- `expert_monthly_allocation.json`: Structured output for integration

##  Tech Stack

- Python · Pandas · NumPy · Statistical Modeling · CSV Automation · Scenario Planning

##  Use Cases

- Resource planning under uncertainty
- Risk-aware staffing decisions
- Financial forecasting with skill-level granularity
- Dashboard-ready insights for stakeholders

##  Future Enhancements

- Role-based allocation logic (Junior vs Senior)
- Real-time data integration
- Cost modeling and optimization



