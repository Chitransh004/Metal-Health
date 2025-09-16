# 🧠 Mental Health in Tech: Workplace Resources & Willingness to Speak Out
📋 Project Overview
This data analysis project explores the relationship between workplace mental health policies and employees' willingness to discuss mental health issues in the technology industry. Using the 2014 OSMI (Open Sourcing Mental Illness) survey data, I analyzed how organizational culture and resources impact employee openness about mental health.
🎯 Business Objective
Primary Goal: To understand how workplace policies and resources influence employees' comfort levels in discussing mental health in tech companies.
Key Questions:

How do workplace mental health resources affect employee willingness to speak out?
What is the awareness level of existing mental health support systems?
How does comfort in discussing mental health compare to physical health discussions?

📊 Dataset Information

Source: Kaggle - OSMI Mental Health in Tech Survey (2014)
Size: ~1,200 responses
Features: Demographics, workplace policies, employee attitudes, mental health history
Data Type: Survey responses (self-reported data)

Key Variables Analyzed:

Demographics (Age, Gender, Country, Role)
Workplace mental health policies availability
Employee comfort levels discussing mental vs. physical health
Awareness of company mental health resources
Treatment history and family mental health background

🛠️ Tools & Technologies

Python Libraries:

pandas - Data manipulation and cleaning
numpy - Numerical computations
matplotlib - Data visualization
seaborn - Statistical visualizations

🧠 Mental Health in Tech: Workplace Resources & Willingness to Speak Out
📋 Project Overview
This data analysis project explores the relationship between workplace mental health policies and employees' willingness to discuss mental health issues in the technology industry. Using the 2014 OSMI (Open Sourcing Mental Illness) survey data, I analyzed how organizational culture and resources impact employee openness about mental health.
🎯 Business Objective
Primary Goal: To understand how workplace policies and resources influence employees' comfort levels in discussing mental health in tech companies.
Key Questions:

How do workplace mental health resources affect employee willingness to speak out?
What is the awareness level of existing mental health support systems?
How does comfort in discussing mental health compare to physical health discussions?

📊 Dataset Information

Source: Kaggle - OSMI Mental Health in Tech Survey (2014)
Size: ~1,200 responses
Features: Demographics, workplace policies, employee attitudes, mental health history
Data Type: Survey responses (self-reported data)

Key Variables Analyzed:

Demographics (Age, Gender, Country, Role)
Workplace mental health policies availability
Employee comfort levels discussing mental vs. physical health
Awareness of company mental health resources
Treatment history and family mental health background

🛠️ Tools & Technologies

Python Libraries:

pandas - Data manipulation and cleaning
numpy - Numerical computations
matplotlib - Data visualization
seaborn - Statistical visualizations


Environment: Jupyter Notebook
Version Control: Git

📁 Project Structure
mental-health-tech-analysis/
├── data/
│   ├── raw/
│   │   └── mental_health_survey.csv
│   └── cleaned/
│       └── mental_health_clean.csv
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_analysis_visualization.ipynb
│   └── 04_final_report.ipynb
├── src/
│   ├── data_cleaning.py
│   ├── visualization.py
│   └── analysis.py
├── reports/
│   ├── case_study.pdf
│   └── presentation.pdf
├── images/
│   ├── demographics_chart.png
│   ├── workplace_resources_distribution.png
│   └── correlation_analysis.png
├── requirements.txt
├── README.md
└── .gitignore
🔍 Key Findings
1. Workplace Policy Impact

Less than 50% of organizations had formal mental health policies
Companies with resources showed significantly higher employee trust levels

2. Awareness Gap

Major disconnect between resource availability and employee awareness
Many employees unaware of existing mental health support systems

3. Discussion Comfort Levels

Employees felt more comfortable discussing physical health than mental health
Organizations with formal support saw increased willingness to discuss mental health

4. Correlation Analysis

Strong positive relationship between resource awareness and willingness to discuss mental health
Family history and treatment experience influenced openness levels

📈 Visualizations
The project includes several key visualizations:

Demographics distribution of survey respondents
Workplace resources availability across organizations
Comfort level comparisons (mental vs. physical health)
Correlation heatmaps showing relationships between variables
Resource awareness by workplace support level

🎯 Business Recommendations
Based on the analysis, I recommend organizations:

Implement Awareness Campaigns - Highlight existing mental health resources
Establish Formal Policies - Create comprehensive mental health policies in every organization
Provide Training - Educate managers and HR on sensitive mental health conversations
Create Anonymous Systems - Implement feedback systems to reduce judgment fears

📝 Data Integrity Considerations

Bias Acknowledgment: Self-reported survey data may contain response bias
Missing Values: Handled missing demographic data through appropriate cleaning techniques
Sample Representation: Majority responses from North America and Europe
Temporal Limitation: Data from 2014 may not reflect current workplace trends

🚀 Getting Started
Prerequisites
bashPython 3.7+
Jupyter Notebook
Installation

Clone the repository:

bashgit clone https://github.com/[your-username]/mental-health-tech-analysis.git
cd mental-health-tech-analysis

Install required packages:

bashpip install -r requirements.txt

Launch Jupyter Notebook:

bashjupyter notebook

Open notebooks/01_data_exploration.ipynb to start exploring the analysis

📊 Sample Code
python# Data loading and basic analysis
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load cleaned data
df = pd.read_csv('data/cleaned/mental_health_clean.csv')

# Analyze comfort levels
comfort_analysis = df.groupby('workplace_resources')['comfort_discussing_mental_health'].value_counts()
print(comfort_analysis)

# Visualization
plt.figure(figsize=(10, 6))
sns.countplot(data=df, x='workplace_resources', hue='comfort_discussing_mental_health')
plt.title('Workplace Resources vs. Comfort Discussing Mental Health')
plt.show()
🤝 Stakeholders

Primary: Employees in the technology industry
Secondary: Employers, HR professionals, workplace policy makers, mental health advocates

📚 References

OSMI (Open Sourcing Mental Illness) Survey, 2014
Kaggle Dataset: Mental Health in Tech Survey

📧 Contact
Chitransh Rahangdale
LinkedIn: www.linkedin.com/in/chitransh-rahangdale

⭐ If you found this analysis helpful, please consider giving it a star!
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

Environment: Jupyter Notebook
Version Control: Git
