# Wuzzuf Jobs
## Wuzzuf is a platform for finding jobs in Egypt, based on your skills and experience.
Using dataset from kaggle.com, we use Spark in Java to build a web application powered by Spring Boot to display analysis of jobs in Egypt. and using some machine learning (e.g. K-Means) algorithms to find insigts in the data.

## Data Set:

Wuzzuf jobs in Egypt data set at Kaggle

   https://www.kaggle.com/omarhanyy/wuzzuf-jobs
   ![Web Page](https://github.com/shrookehab/Wuzzuf-Jobs-Analysis/blob/master/src/main/resources/files/Screenshot%202022-06-04%20at%2012-52-13%20Wuzzuf%20jobs%20services.png)
   
## Task: 

•	Build all java needed classes (POJO , DAO, web service and a tester client for the web service)

•	Make a web service to get the following from the data set:
   
  1.	Read the dataset, convert it to DataFrame or Spark Dataset, and display some from it.

  2.	Display structure and summary of the data.

  3.	Clean the data (null, duplications)

  4.	Count the jobs for each company and display that in order (What are the most demanding companies for jobs?)

  5.	Show step 4 in a pie chart 
    
  ![Jobs By Company Pie Chart](https://github.com/shrookehab/Wuzzuf-Jobs-Analysis/blob/master/src/main/resources/files/jobsByCompanyPieChart.jpg)

  6.	Find out what are the most popular job titles.

  7.	Show step 6 in bar chart
   
  ![Popular Job Titles Bar Chart](https://github.com/shrookehab/Wuzzuf-Jobs-Analysis/blob/master/src/main/resources/files/PopularJobTitlesBarChart.jpg)

  8.	Find out the most popular areas?

  9.	Show step 8 in bar chart 
  
  ![Popular Areas Bar Chart](https://github.com/shrookehab/Wuzzuf-Jobs-Analysis/blob/master/src/main/resources/files/PopularAreasBarChart.jpg)

  10.	Print skills one by one and how many each repeated and order the output to find out the most important skills required?

  11.	Factorize the YearsExp feature and convert it to numbers in new col. (Bonus )

  12.	Apply K-means for job title and companies (Bonus)
  
  ## Acknowledgements

* [Apache Spark](https://spark.apache.org/documentation.html)
* [Spring Web Service](https://start.spring.io/)
* [Tablesaw](https://javadoc.io/doc/tech.tablesaw/tablesaw-core/latest/overview-summary.html)
