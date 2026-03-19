# TikTok Claims Classification: Data Inspection & Preparation

📌 About This Project

This project is a critical component of the TikTok Claims Classification initiative, designed to improve the efficiency of content moderation through predictive analytics. As a Data Analyst on the team, my role was to navigate the Plan and Analyze stages of the PACE framework to ensure the dataset was structurally sound and statistically insightful before model construction.

By performing rigorous Exploratory Data Analysis (EDA) and Feature Engineering, I identified key behavioral markers that distinguish between unsourced claims and personal opinions.
Key Technical Contributions:

    Data Health & Integrity: Conducted a comprehensive audit using data.info() and data.describe(), identifying 298 null values and addressing significant right-skewed distributions in engagement metrics.

    Feature Engineering: Engineered new engagement rate variables—likes_per_view, comments_per_view, and shares_per_view—to normalize interaction data across varying video lengths and view counts.

    Bivariate Analysis: Leveraged groupby() and agg() to uncover a high correlation between banned authors and the posting of "claims," providing a roadmap for prioritized moderation.

    Stakeholder Communication: Synthesized complex technical findings into an Executive Summary for cross-functional leadership, focusing on operational impact and backlog reduction.

Tech Stack:

    Language: Python (v3.x)

    Libraries: Pandas, NumPy

    Tools: Jupyter Notebook, GitHub
