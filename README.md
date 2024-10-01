# Analysis of the Job Market for Jobs Connected with Data in European Union

Welcome to the unpredictable world of data. In this project I've tried to show what this industry consists of with the help of Luke Barrousse's Course on Python. 

## You'll be able to gather insights on:

* **Skill Prioritization:**  The analysis reveals the top five skills crucial for success across four prominent data-related professions, offering a clear picture of skill importance and market demand.
* **Demand Fluctuations:** Dynamic visualizations track the ebb and flow of skill demand throughout 2023, pinpointing the year's most impactful trends and emerging skill sets.
* **Optimal Skill Combinations:** A strategic scatterplot uncovers the most effective skill combinations for maximizing career prospects within the competitive data job market.
* **Exploratory Data Analysis (EDA):** A comprehensive EDA provides a holistic view of the data roles market, offering a deeper understanding of trends and opportunities.
* **Visualized Skill Demand:**  Visual representations clarify the demand for the most popular skills across four key data professions.


## 1. Exploratory Data Analysis
First of all, what countries are the most active in the data market?

![alt text](<The Graph Pictures/Countries_Sorted_by_Job_count.png>)

The output shows that the France is the leader by far, which may suggest that this country is the best for people searching for a job in Data.

Next, it is important to know: what are the chances to find a job, which doesn't require a degree? or a job, where it's possible to work from home?

![alt text](<The Graph Pictures/Benefits.png>)

As seen on the graph, it's important to be present at the office for the majority of employers, however degree is considered to be a nice add-on, rather than requirement.

Also, it is important to understand, who dictates the trends on the job market?

![alt text](<The Graph Pictures/Companies_trend-setters.png>)

The graph tells us that the biggest trend-setter is Confidenziale. However, there are some other companies, who are more than active.

Most importantly, everyone wants to know the pay. Do companies in EU share this info in the postings?

![alt text](<The Graph Pictures/Info_on_salary.png>)

Yes, the answer is yes. Undoubtebly.

So, what can a, let's say, Data Analyst expect from his salary?

![alt text](<The Graph Pictures/da_salary_bplot.png>)

Well, around $75k a year median, not bad for a start.

## 2. Counts of Skills

The most important thing to know about a profession is to know what do you have to do. But if we want to count that, we would need to calculate the probability of the given skill, appearing in a job posting of the given job role:

![alt text](<The Graph Pictures/Demanded_skills.png>)

This dashboard gives a deep dive into the peculiarities of 4 most popular roles in the world of data. The most demanding being Data Engineer, and the less demanding being the Business Analyst. But, in my humble opinion, it is connected with the role itself being not massively popular, hence different employers might require polarizing sets of skills and abilities.

1. **Business Analyst**: SQL (33%) is the leading skill, followed closely by Excel (29%). This indicates a strong reliance on data manipulation and reporting tools in this role.

2. **Data Analyst**: SQL (32%) and Python (31%) hold foundational places, emphasizing the importance of both database management and programming in data analysis jobs. Power BI (22%) and Tableau (20%) are also notable, reflecting the demand for data visualization skills.

3. **Data Engineer**: Python (56%) is predominantly required, showcasing its critical role in data engineering tasks. SQL (44%) follows closely, reaffirming the necessity for data manipulation skills, and Azure (35%) highlights a growing need for cloud platform proficiency.

4. **Data Scientist**: Python (63%) takes the lead, indicating its preeminence in data science. SQL (21%) is essential for data extraction and management, while skills in Azure (14%) and Spark (13%) highlight the field's increasing focus on cloud services and big data technologies.

Overall, the chart suggests that SQL and Python are essential across most data-related professions, with a notable emphasis on visualization tools for analysts. Furthermore, proficiency in cloud technologies, particularly Azure, is increasingly important for roles such as Data Engineer and Data Scientist.

## 3. Trending skills

It's great to know about popular skills, but what's better is to notice the skills, which are only starting to be trending earlier, than the majority pf people in the industry. 

![alt text](<The Graph Pictures/Trending_skills.png>)

These are the skills, that have shown the biggest growth in demand, and had more than 50 counts per month. It's cool to find out about these, but without the core of the most demanded skills, it's a losing game. But do any of the necessary skills lose their popularity?

![alt text](<The Graph Pictures/GRAph.png>)

As can be seen on this chart (if the chart is too small for you, it is accessible through the graph pictures folder), none of the most demanded skills show significant signs of becoming less popular; neither on the general chart, nor on the chart specific for the role.
There are some minor differences from month to month, but they are none that worth mentioning.

## 4. Salary Analysis

One of the most important things while pursuing a career in data is a paycheck. There are several roles with their differences and similarities, which result in the difference in salary

![alt text](<The Graph Pictures/EU_Salaries.png>)

This graph presents several boxplots for different jobs in data field, giving a deep dive in what might be the best choice in terms of material potential. As can be seen, the most high-paying jobs in data are Scientists and Engineers, so it makes sense to observe them more closely, what skills pay the most? Which of the necessary skills pay more?

![alt text](<The Graph Pictures/DES_paying_skills.png>)

On this plot everything becomes clear in terms of skills. Yes, there are some more high-paying skills with the count of more than 30, yet the difference between them and the most relevant skills with counts over several hundreds, it is a big question whether most high-paying skills worth it.

## 5. Optimal Skills

The highest-paying skills were discovered, the most popular too, yet the questions remains: what are the most optimal. Well, the best thing to discover through is scatterplot.

![alt text](<The Graph Pictures/Optimal.png>)

Now **that** is a clear representation of what is worth observing. It is a bit clustered around the center, but the most optimal skills are on the right, like SQL and Python, and on the top, like airflow and spark

Here it is. The deepest possible dive in data industry, as I'd say.

