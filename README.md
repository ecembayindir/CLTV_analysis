<h1 align="center">CLTV Prediction with BG-NBD and Gamma-Gamma Models</h1>

<br/>

<h2>🚀 <strong>Project Overview</strong></h2>
<p>
This project focuses on predicting the Customer Lifetime Value (CLTV) for a shoe company. By analyzing the shopping behavior of customers, we estimate their future value to help define a strategic roadmap for sales and marketing. Using advanced statistical models like <strong>BG-NBD</strong> and <strong>Gamma-Gamma</strong>, this project demonstrates how to identify high-value customers and optimize business strategies for long-term growth.
</p>

<h2>📄 <strong>Dataset Story</strong></h2>
<p>
The dataset consists of historical shopping behavior from customers who made OmniChannel purchases (both online and offline) in 2020–2021. Unfortunately, the dataset is private, and therefore, it is not included in this repository. However, the analysis, methodology, and scripts can be applied to similar datasets to reproduce the results.
</p>

<h3>Key Features:</h3>
<ul>
  <li><strong>master_id:</strong> Unique customer identifier</li>
  <li><strong>order_channel:</strong> Platform used for shopping (Android, iOS, Desktop, Mobile, Offline)</li>
  <li><strong>first_order_date:</strong> Date of the first purchase</li>
  <li><strong>last_order_date:</strong> Date of the last purchase</li>
  <li><strong>order_num_total_ever_online:</strong> Total number of online purchases</li>
  <li><strong>order_num_total_ever_offline:</strong> Total number of offline purchases</li>
  <li><strong>customer_value_total_ever_online:</strong> Total spending online</li>
  <li><strong>customer_value_total_ever_offline:</strong> Total spending offline</li>
  <li><strong>total_order_num:</strong> Combined total purchases</li>
  <li><strong>total_order_value:</strong> Combined total spending</li>
</ul>

<h2>📈 <strong>Project Workflow</strong></h2>
<ul>
  <li><strong>Data Preparation:</strong> Cleaned data, handled outliers, and created new features for analysis.</li>
  <li><strong>CLTV Data Structure:</strong> Built key metrics like recency, frequency, and monetary value in weekly terms.</li>
  <li><strong>Model Implementation:</strong> Used BG-NBD for purchase prediction and Gamma-Gamma for monetary value estimation.</li>
  <li><strong>CLTV Segmentation:</strong> Divided customers into segments (A, B, C, D) based on 6-month CLTV predictions.</li>
</ul>

<h2>🛠️ <strong>Methods Applied</strong></h2>
<ul>
  <li><strong>Outlier Treatment:</strong> Applied interquartile range (IQR) to suppress outliers in spending and order counts.</li>
  <li><strong>BG-NBD Model:</strong> Predicted the expected number of purchases over 3 and 6 months.</li>
  <li><strong>Gamma-Gamma Model:</strong> Estimated the average revenue per transaction.</li>
  <li><strong>CLTV Calculation:</strong> Combined purchase predictions and monetary estimates to compute customer lifetime value.</li>
  <li><strong>Segmentation:</strong> Categorized customers into four CLTV-based segments for targeted strategies.</li>
</ul>

<h2>🔧 <strong>Tools & Technologies Used</strong></h2>
<div align="center">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python"/>
    <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
    <img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
    <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
    <img src="https://img.shields.io/badge/lifetimes-FFD700?style=for-the-badge" alt="Lifetimes"/>
    <img src="https://img.shields.io/badge/Jupyter-DA5B0B?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
</div>

<h2>📊 <strong>Key Insights</strong></h2>
<ul>
  <li><strong>High-Value Customers:</strong> Identified top customers contributing significantly to revenue over the next 6 months.</li>
  <li><strong>Segment Insights:</strong> Customers in segment A have higher frequency and spending, offering maximum value.</li>
  <li><strong>Strategic Roadmap:</strong> Recommendations for personalized campaigns targeting high-CLTV segments.</li>
  <li><strong>OmniChannel Behavior:</strong> Offline and online purchase patterns reveal opportunities for cross-channel strategies.</li>
</ul>

<h2>📢 <strong>Contact</strong></h2>
<ul>
    <li><a href="https://www.linkedin.com/in/yourusername/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"/></a></li>
    <li><a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email"/></a></li>
</ul>

<p align="center">&copy; 2025 Your Name. All rights reserved.</p>

<hr>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ecembayindir&repo=CLTV_analysis&label=Repository%20views&color=0e75b6&style=flat" alt="Repository Views">
</p>
