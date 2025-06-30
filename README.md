# RA-submission
## Household Power Consumption Analysis with LLM

### Author
**Deena Lad** 

### LLM Used
- **Primary LLM**: Groq API with meta-llama/llama-4-scout-17b-16e-instruct model
- **Task**: Natural language to pandas code generation for data analysis

### Overview
This project demonstrates the use of Large Language Models (LLMs) to perform data analysis on household power consumption data through natural language queries. The system converts plain English questions into executable pandas code using the Groq API.

### Tasks Completed

#### 1. Data Loading and Preprocessing
- Loaded UCI Household Electric Power Consumption dataset
- Cleaned missing values and converted data types
- Set datetime index for time-series analysis

#### 2. LLM Integration
-  Integrated Groq API for code generation
-  Implemented natural language to pandas code conversion

#### 3. Analysis Queries Completed
1. **Average Power Consumption**: Calculated average active power consumption for March 2007
2. **Peak Usage Analysis**: Found the hour with highest power usage on Christmas 2006
3. **Weekday vs Weekend Comparison**: Analyzed energy usage patterns between weekdays and weekends
4. **High Consumption Days**: Identified days where energy consumption exceeded 5 kWh
5. **Trend Visualization**: Plotted energy usage trend for the first week of January 2007
6. **Voltage Analysis**: Calculated average voltage for each day in the first week of February 2007
7. **Correlation Analysis**: Examined correlations between global active power and sub-metering values

### Repository Structure
```
├── llm_queries.ipynb          # Main Jupyter notebook with analysis
├── README.md                  # This file
└── requirements.txt           # Python dependencies
```
