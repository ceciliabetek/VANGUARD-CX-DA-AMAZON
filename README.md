# VANGUARD-CX-DA-AMAZON
IronHack Customer Experience Data Analyst project - Amazon group


## Project Introduction:

In this project, we act as a data analytics team working for Vanguard, tasked with analyzing customer experience data from a digital experiment conducted on a new application.

The experiment focuses on changes to the user interface (UI), including clearer instructions and improved prompts, with the aim of making the process smoother and more intuitive. The goal is to determine whether these changes lead to a better user experience and higher process completion rates.

The experiment was conducted over a three-month period, from 15 March to 20 June, using an A/B testing approach:
- Control group: Clients using the older version of the application  
- Test group: Clients using the newer version of the application  

Based on the results of our analysis, we provide insights and recommendations on whether the new design should be fully launched by the company.


## Findings and recommendations:

### Findings:

The analysis revealed several notable patterns in client demographics and behavior.

**Gender distribution** is relatively balanced between male and female clients. A big proportion of records are labeled as "unknown", which may indicate data capture limitations or users who chose not to disclose this information.

**Age distribution** is fairly uniform between 20 and 65 years old, while significantly fewer clients fall outside this range. This suggests that the platform is primarily used by individuals in active working and early retirement stages.

**Client tenure** shows concentrations around 5 and 20 years, indicating the presence of both relatively new and long-term loyal customers.

**Digital engagement** is strongest in the mid-range, with most clients logging in between 3 and 7 times. Very low and very high engagement levels are less common.

**Customer support activity** is generally low, with most clients making between 1 and 2 support calls over the six-month period.

**Account balances** are heavily concentrated in lower ranges (below $100,000), with a sharp decline in the number of clients as balances increase. This indicates that the majority of users are small to mid-level investors.

### Recommendations:

* Delay full rollout until the experience meets the 5pp improvement threshold;
* Focus on fixing early-stage friction, where drop-offs increased;
* To fix this friction, better usage guidance at the start of the process could be useful;
* Run a targeted follow-up A/B test to validate incremental improvements;
* To assess whether the redesign improves the overall client experience beyond task completion, monitor CX metrics such as      support calls and repeat usage.

## Project Structure:

    C:.
│   .DS_Store
│   .env
│   .gitattributes
│   .gitignore
│   note.txt
│   README.md
│
├───Data
│   ├───Processed
│   │       df_client_usage.csv
│   │       df_exp_visits.csv
│   │       df_final_demo_clean.csv
│   │       df_final_experiment_clients_clean.csv
│   │       df_final_web_merged.csv
│   │       df_kpi_clients.csv
│   │       df_web_visit_metrics_final.csv
│   │
│   └───Raw
│           df_final_demo.csv
│           df_final_experiment_clients.csv
│           df_final_web_data_pt_1.csv
│           df_final_web_data_pt_2.csv
│
└───Notebooks
        01_DS_data_exploration.ipynb
        02_rq_df_cleaning.ipynb
        03_DS_monthly_usage_analysis.ipynb
        04_rq_experiment_metrics.ipynb
        05_DS_ab_test_perf_analysis.ipynb
        06_hypothesis_testing.ipynb



Presentation & Tableau link:

https://public.tableau.com/views/ProjectVanguard-TeamAmazon/Dashboard23?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Checkpoints and feedback:

https://docs.google.com/document/d/103C8WJMz3wGycB5IoNe2rsMmI0zSCz1LeylHe0vsqyM/edit?tab=t.0


Google Slides Link:

https://docs.google.com/presentation/d/1LDqqTThuMq5RHpGvpPxH-7z6Mthtvqq0a-W5QhI6uLw/edit?slide=id.g3bcbc35631d_0_74#slide=id.g3bcbc35631d_0_74

