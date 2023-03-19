# Data Science Job Posting On Glassdor Data Analysis
The main goal of the project is to extract meaningful insights from the job posting data to help job seekers, recruiters, and hiring managers make informed decisions related to data science job opportunities. To achieve this, the project looks at various factors such as salary, location, firm, sector, industry type, and skills to determine whether there is a link between these factors and the differences detected in the data.

## The dataset for this project has been taken from the URL link:
[Data Science Job Posting on Glassdoor](https://www.kaggle.com/datasets/rashikrahmanpritom/data-science-job-posting-on-glassdoor)

## Data Analysis and Data Visualizations
**1. Top ten highest-paid companies for data scientist job role**<br>

<img width="474" alt="Top 10 highest-paid companies" src="https://user-images.githubusercontent.com/122247029/226216119-faa13ede-d137-4a14-9153-d4b4ba297cda.PNG">

[Application Used: Bullet Graph and Reference Line, Filter, Marks Card]<br>
The purpose of this analysis is to gain insights into the salaries offered to data scientists by various companies. The above bullet graph depicts the top ten companies that offer the highest compensation to data scientists. The x-axis of the graph represents the base salary, while the y-axis indicates the company names. The graph incorporates a rank filter, indicating the rank of each company in terms of the salary offered to data scientists. Additionally, a job title filter is added to select the data scientist job role. The graph reveals that Google offers the highest salary for data scientists, followed by Amazon, Facebook, and eBay. A reference line is included in the chart, dividing the graph into two equal parts based on the average salary. The average base salary of all ten companies is approximately 1813900USD. Comparing the average salary with that of each company demonstrates that Google, Amazon, Facebook, and eBay offer the highest salaries. It is important to note that there is a significant difference in wages offered by Google compared to the second-highest company. However, the salaries of the other nine companies do not differ significantly. By changing the job role filters, one can explore the salaries offered by different companies for various job roles.<br>

**2. Analysis of the salary offered by different companies based on years of experience**<br>

<img width="589" alt="Analysis of the salary offered by different companies based on years of experience" src="https://user-images.githubusercontent.com/122247029/226216472-ea1e90c1-2986-41f4-a5d6-10debcbeb6f8.PNG">

[Application Used: Scatter Plot and Set, Filter, Marks Card]<br>
This analysis provides insights into the salary ranges offered by different companies based on years of experience. The scatter plot graph depicts the correlation between salary and experience, with Facebook offering the highest compensation for 21 years of experience and Envision LLC providing the lowest pay for one year of experience. The x-axis represents base salary, while the y-axis represents years of experience. To provide a clearer view of the data, a set was created to show salaries offered by different companies for more than five years of experience, with a box representing the range and a circle showing any outliers. This set enables us to understand the salary range for a specific range of experience. By adjusting the settings, we can analyze the salaries offered for different fields such as more than five years or less than five years of experience. It's important to note that companies offer different salary ranges for various years of experience, and there is no specific way to analyze base salaries for additional years of experience. Other factors like skills and requirements might also influence wages.<br>

**3. Job opportunities in different states in the USA**<br>

<img width="588" alt="Geographical Map for job oppourtutinities" src="https://user-images.githubusercontent.com/122247029/226216768-9415884b-457e-4934-8eb6-2976f3aef957.PNG">
<img width="585" alt="Filtered geographical map" src="https://user-images.githubusercontent.com/122247029/226216847-1f17bc18-9197-424d-955e-1028ecb99c85.PNG">

[Application: Geographic Map, Filter, Marks Card]<br> 
The above graph displays a geographical map of various job roles in different states of the USA, based on their longitude and latitude. The color indicates the job titles, and the data is filtered on the sum of base salary. This chart helps us analyze job opportunities in different locations. It shows that Data Engineering is the most common job role offered in the USA, followed by Data Scientist and Data Analyst. However, Machine Learning job opportunities are relatively scarce and only available in a few states. The graph also highlights that most of the job opportunities are concentrated in the eastern part of the USA. With the help of filters, we can analyze specific job roles and see which jobs are offered in which states. This information can assist job seekers in choosing the best location to apply for jobs based on their preferences and skillset.<br>

**4. Relation between Education, Years of Experience, and Base salary**<br>

<img width="585" alt="box plot" src="https://user-images.githubusercontent.com/122247029/226216973-3c2f3efe-73b7-4d44-a263-60704101be29.PNG">

The box and whisker plot presented above provides a visual representation of the relationship between education, years of experience, and base salary. It displays the distribution of data points for different education levels based on wage and years of experience. The X-axis represents education levels, while the y-axis represents the sum of the base salary. Additionally, the color of the plot shows the count of years of experience, and details are provided for the company name. The analysis of the graph reveals that most companies require master's and Ph.D. degrees, which increases the likelihood of better job opportunities and higher salaries for individuals with these degrees. Conversely, high school and some college graduates have minimal chances of obtaining a job with a high salary. This visualization can provide useful insights for making informed decisions related to career choices and educational paths.<br>

**5. Maximum and minimum salary offered for the different sectors for data scientist**<br>

<img width="585" alt="maximum and minumin" src="https://user-images.githubusercontent.com/122247029/226217178-975ea45c-6444-40d0-a5ed-7ef3f30b3c4c.PNG">

[Application Used: Bar Chart, Parameter, Sort, Filter, Marks Card]<br>
The above visualization is a bar graph that displays the average salaries offered for different job roles in various sectors. The X-axis shows the sectors, and the different job titles are broken down within each sector. The Y-axis shows the average salary offered for each job role. The graph also includes a filter parameter that allows us to dynamically modify the number of top deals displayed. The sectors are sorted alphabetically, and the top 12 highest salaries are displayed. It is evident from the graph that data engineers, data scientists, and data analysts are grouped together as they have similar job profiles. The Finance Aerospace & Defense sector offers the highest salary for these job roles. On the other hand, the Information Technology sector has a good job opportunity for machine learning engineers. This analysis provides insights into how different industries offer varying salaries for different job roles. It can help job seekers understand which sectors to target based on their desired job role and salary expectations. Similarly, companies can also use this graph to benchmark their salaries against industry standards and ensure they are offering competitive salaries to attract top talent.<br>

**6. Average salary offered by different sectors for different job roles**<br>

<img width="576" alt="tree map" src="https://user-images.githubusercontent.com/122247029/226217281-a781a192-137b-44c3-8d7b-4a307982874f.PNG">

[Application Used: TreeMap, Filter, Marks sheet]<br>
The above visualization is a TreeMap that illustrates the distribution of job titles across various industries. The size of the boxes represents the number of job openings, and the color indicates the relative number of jobs in each sector. The darker shade represents a higher number of job openings, and the lighter shade represents a lower number of job openings. The analysis of the TreeMap indicates a significant increase in data science jobs each year. Based on the data, industries such as Biotech & Pharmaceutical, Insurance, Health care, and Aerospace & Defense have a high demand for data scientists. In contrast, the retail sector has the least demand for data scientist positions. The analysis also reveals that many companies have career opportunities based on data science. Overall, the TreeMap provides an easy-to-understand visualization of job opportunities in various industries, and it can help job seekers to identify industries with high job openings for their job titles.

## Dashboard

<img width="543" alt="dashboard 1" src="https://user-images.githubusercontent.com/122247029/226217443-d14bfa8c-8926-4c35-8e88-336feaee480d.PNG">
<img width="549" alt="2222" src="https://user-images.githubusercontent.com/122247029/226217473-98110d96-085b-4fed-8980-99ae6ec13e22.PNG">

The aim of our project was to analyze the job opportunities and salaries offered in the field of data science across the United States. To achieve this, we utilized a dataset that provided information on various job roles, companies, industries, and locations, along with their associated base salaries.Our analysis was presented in the form of a dashboard, which included four linked graphs based on the base salary. These graphs provided valuable insights into the job market, highlighting different aspects of job opportunities and salaries for data science roles.<br>

The first graph was a geographic map that showcased job opportunities in different states across the US. The map was color-coded, with each color representing a specific job role. We could analyze the spread of job roles across different states, providing a broad overview of job opportunities available in each state.<br>

The second graph displayed the top ten highest-paid companies for data scientist job roles. This graph provided insights into the top-paying companies, their base salaries, and job titles. By analyzing this graph, we could understand the companies that pay the highest wages for data science roles.<br>

The third graph was a TreeMap that showed the number of jobs in different industries for data science roles. The TreeMap was structured based on the job title size and different sectors, providing insights into the number of jobs available in each industry.<br>

##Storytelling


The fourth graph showcased the maximum and minimum salaries offered for different job roles based on location. This graph presented a dual-axis chart, with the X-axis representing the location and the Y-axis displaying the maximum and minimum salaries. By analyzing this graph, we could determine the location that offers the highest salaries for data science roles.

Our analysis revealed that San Francisco was the top contributor, offering the highest salaries for data science roles. This information is valuable for job seekers looking for data science roles, highlighting the importance of location in considering job opportunities. Overall, our dashboard provided valuable insights into the job market for data science roles in the United States.

