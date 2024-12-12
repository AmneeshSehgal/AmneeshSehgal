Exploratory Data Analysis 
 
Project Description: Exploratory Data Analysis of School Distribution in Vancouver 
Project Title: School Distribution in Vancouver: A Focus on Renfrew-Collingwood 
Objective: The primary goal of this project is to perform an exploratory data analysis (EDA) on the City of Vancouver's school data to understand the distribution of different school categories across the city, with a specific focus on the Renfrew-Collingwood area. By analyzing the number of public, independent, and StrongStart BC schools, we aim to identify areas with the highest concentration of schools and gain insights into the educational resources available in different neighborhoods. 

Dataset: The dataset consists of a list of schools in Vancouver, with the following information:  
*   ADDRESS: The street address of the school. 
*   SCHOOL_CATEGORY: The type of school (e.g., Independent School, Public School, StrongStart BC). 
*   SCHOOL_NAME: The official name of the school. 
*   Geom: Geographical coordinates of the school in JSON format. 
*   Geo Local Area: The local area or neighborhood where the school is located. 
*   geo_point_2d: Latitude and longitude of the school in a simplified format. 
 
Methodology: 
 Data Collection and Preparation: 
*   Data was injected into AWS S3. 
*   Data profiling and cleaning were performed using AWS Data Group services. 
*   An ETL pipeline was created using AWS Glue to prepare the data for analysis. 
 
Descriptive Statistics: 
 
*   The total number of schools in Vancouver was calculated, along with the number of schools in each category (public, independent, StrongStart BC). 
*   The number of schools of each category in the Renfrew-Collingwood area was identified. 
 
Area Focus: 
 
*   The Renfrew-Collingwood area was identified as having the highest number of schools. The distribution of school types within this area was analyzed. 
 
Comparative Analysis: 
 
*   The proportion of each school type in Renfrew-Collingwood was compared to the overall proportion of each school type in the entire city of Vancouver. 
 
Insights and Findings: 
 
*   The city of Vancouver has a total of 194 schools, including 121 public schools, 54 independent schools, and 19 StrongStart BC schools. 
*   The Renfrew-Collingwood area has 13 public schools, 6 independent schools, and 2 StrongStart BC schools, demonstrating a high concentration of educational resources in this area. 
*   Renfrew-Collingwood's distribution of school types was compared to the overall city distribution to highlight any significant differences. For example, is the proportion of independent schools higher or lower in Renfrew-Collingwood compared to the city average? 
Conclusion: 
 
*   The analysis highlighted the concentration of schools in the Renfrew-Collingwood area. Further analysis could explore factors contributing to this concentration, such as population density, demographics, or city planning. 
 
Tools and Technologies: 
 
*   AWS S3 (for data storage) 
*   AWS Data Group services (for data profiling and cleaning) 
*   AWS Glue (for ETL) 
*   AWS KMS (for encryption) 
*   AWS CloudWatch (for monitoring) 
*   AWS CloudTrail (for user activity tracking) 
 
Deliverables: 
 
*   A summary report outlining the analysis process, findings, and comparisons between Renfrew-Collingwood and the city of Vancouver. 
 
This EDA project provides insights into the distribution of schools in Vancouver, focusing on the Renfrew-Collingwood area and its high concentration of educational resources. 
![WhatsApp Image 2024-12-11 at 8 25 20 PM](https://github.com/user-attachments/assets/fd3c5f15-bdbb-48ce-b2cd-3a3d75d7e8ee)

Descriptive Analysis 
 
Project Description: Descriptive Analysis of School Distribution in Vancouver 
Project Title: Understanding School Distribution in Vancouver 
Objective: The primary goal of this project is to conduct a descriptive analysis of the City of Vancouver's school data. Through this analysis, we aim to summarize key characteristics of school distribution across the city, identify patterns in school locations, and provide a comprehensive overview of the educational resources available.

Dataset: The dataset consists of a list of schools in Vancouver, with the following information: 
 
*   ADDRESS: The street address of the school. 
*   SCHOOL_CATEGORY: The type of school (e.g., Independent School, Public School, StrongStart BC). 
*   SCHOOL_NAME: The official name of the school. 
*   Geom: Geographical coordinates of the school in JSON format. 
*   Geo Local Area: The local area or neighborhood where the school is located. 
*   geo_point_2d: Latitude and longitude of the school in a simplified format. 
 
Methodology: 
 
Data Collection and Preparation: 
 
*   Data was injected into AWS S3. 
*   Data profiling and cleaning were performed using AWS Data Group services. 
*   An ETL pipeline was created using AWS Glue to prepare the data for analysis and to calculate the number of public schools in the city. 
 
Descriptive Statistics: 
 
*   Calculated the total number of schools in Vancouver. 
*   Calculated the number of schools in each category (public, independent, StrongStart BC). 
*   Determined the distribution of schools across different local areas (Geo Local Area) within Vancouver. 

