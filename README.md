![telecom](https://github.com/user-attachments/assets/f79da395-7b9a-491c-b7d2-bcc10435f0fa)

# Customer-Churn-Analysis (Ongoing Project)
This is a semester project on customer churn analysis of a telecom company

# Objectives

<ol>
  <li>To analyze customer churn in the telecom industry and understand the factors contributing to it.</li>
  <li>To examine and analyze the impact of price and service reliability</li>
  <li>To analyze patterns in customer behavior and provide actionable insights and recommendations to reduce churn rates effectively.</li>
</ol>

# Methodology
<ol>
  <li>Problem Identification </li>
  <li>Data Collection/gathering</li>
  <li>Data Cleaning/transformation</li>
  <li>Exploratory Data Analysis(EDA) and Feature Engineering</li>
  <li>Data Visualisation</li>
  <li>Report generation/Suggestions for improvement</li>
</ol>

### <a href="https://accelerator.ca.analytics.ibm.com/bi/?perspective=authoring&pathRef=.public_folders%2FIBM%2BAccelerator%2BCatalog%2FContent%2FDAT00148&id=i9710CF25EF75468D95FFFC7D57D45204&objRef=i9710CF25EF75468D95FFFC7D57D45204&action=run&format=HTML&cmPropStr=%7B%22id%22%3A%22i9710CF25EF75468D95FFFC7D57D45204%22%2C%22type%22%3A%22reportView%22%2C%22defaultName%22%3A%22DAT00148%22%2C%22permissions%22%3A%5B%22execute%22%2C%22read%22%2C%22traverse%22%5D%7D">View Dataset</a>

# Data Preparation
<ol>
  <li>Removed duplicates</li>
  <li>Filled Null values by grouping the missing values with supporting columns</li>
  <li>Fixed datatypes for easier merging</li>
  <li>Performed left join with demographics as the main table and dropped population table</li>
  <li>Encoded columns for easier correlation check</li>
  <li>Created temporary features to perofrm checks</li>
  <li>Outliers do exist in age and toal revenue(reason: old customers 6 years approx)</li>
</ol>


#Initial Findings:

As per the initial dataset the company lost around 26% of its customers in just 3 months
- Gender not a factor
- Age had positive correaltion
- Satisfaction score had negative correlation
- Company Add ons have lesser churn, third party has no such relation

# Key findings
The churn analysis highlights that customer age, tenure, contract type, and value-added
services are key factors influencing retention. High churn rates among fiber optic users and
monthly subscribers, especially in areas like San Diego, signal areas for improvement. Bundled
services and longer-term contracts reduce churn, while third-party streaming offerings may
weaken loyalty. By implementing targeted, department-specific strategies based on these
insights, organizations can strengthen customer satisfaction, loyalty, and long-term value.
