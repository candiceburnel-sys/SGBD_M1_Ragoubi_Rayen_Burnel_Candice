# SGBD_M1_Ragoubi_Rayen_Burnel_Candice
Case study on Relational Database Systems (RDBMS) for Banque Internationale à Luxembourg (BIL). Includes the company description, transaction analysis and fraud detection using Python.

<h1 align="center"><u><b> 🏦 BIL Bank Transaction Management & Data Analysis Project </b></u></h1>

📖 **Project Overview**

This project focuses on the Banque Internationale à Luxembourg (BIL), the oldest financial institution in Luxembourg (est. 1856). With over 165 years of history and €20 billion in assets, BIL must navigate modern financial challenges using robust data systems.

Our objective was to bridge the gap between regulatory requirements and technical implementation by building a data analysis tool capable of monitoring transactions and detecting fraud.

🏛️ **About BIL**

> • Legacy: Founded in 1856, supporting industrial development.  
> •	Pillars: Retail Banking, Private & Wealth Management, and Corporate Banking.  
> •	Global Presence: Active in Luxembourg, Switzerland, the Middle East, and Asia.  
> •	Commitment: Strong focus on CSR (Corporate Social Responsibility) and ESG criteria to ensure ethical governance.

⚖️ **Regulatory & Technical Context**

The BCBS 239 Challenge: To comply with the BCBS 239 regulation (Basel Committee), BIL requires a solid database system. This regulation mandates:
> •	High data quality and accuracy.  
> •	Strong data governance.  
> •	Efficient risk data aggregation.  

Why a Relational Database? We rely on RDBMS (Relational Database Management Systems) like Oracle or MySQL because they offer:

> •	High Security: Essential for financial data.  
> •	Data Consistency: Ensuring every transaction is accurately recorded.  
> •	Volume Management: Handling hundreds of thousands of daily transactions.  

🐍 **Python Data Analysis (Google Colab)**

In the SCRIPT/ folder, you will find our Python analysis. We processed a dataset of simulated banking transactions to extract key insights and ensure compliance.

📊 Key Insights Found:

> •	Volume Analysis: Detailed distribution of Debit vs Credit transactions.  
> •	Demographics: Profiling of customers by Age (Min/Max/Average) and Location.  
> •	Financial Health: Analysis of Account Balances and average transaction amounts.

🚨 Suspicious Activity Detection

One of the core features of our script is a fraud detection rule based on behavioral patterns.

> •	Rule Applied: We flagged transactions where the Customer Age is ≤ 25 and the Amount is in the top 10% (≥ €701.31).  
> •	Result: The system successfully identified 56 suspicious transactions that require manual review by the compliance team.

📁 **Project Structure**

> •	📂 DATA/: Contains the raw Excel transaction datasets.  
> •	📂 SCRIPT/: Contains the Google Colab Notebook (.ipynb) with full Python code, visualizations (Pie charts, Histograms), and fraud detection logs.  
> •	📂 DOCUMENTS/: Project documentation and oral presentation support.

🏁 **Conclusion**  

By combining a deep understanding of BIL’s historical background with modern Python data analysis, we demonstrated how technology helps a traditional bank meet the rigorous standards of today’s financial regulations.


