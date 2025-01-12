# Case Study: How does a bike-share navigate speedy success?
## Introduction
In this case study, I work for a fictional company, Cyclistic, along with some key team members.
## Scenario
I am a junior data analyst working on the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, my team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve our recommendations, so they must be backed up with compelling data insights and professional data visualizations.

## Characters and teams
* **Cyclistic**: A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use the bikes to commute to work each day.
* **Lily Moreno**: The director of marketing and my manager. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program. These may include email, social media, and other channels
* **Cyclistic marketing analytics team**: A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy. I joined this team six months ago and have been busy learning about Cyclistic’s mission and business goals—as well as how I, as a junior data analyst, can help Cyclistic achieve them.
* **Cyclistic executive team**: The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program.
## About the company
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime.  

Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.  

Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a solid opportunity to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.  

Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends.

In order to answer the business questions, I follow the steps of the data analysis process:
- [Ask](#ask)
- [Prepare](#prepare)
- [Process](#process)
- [Analyse](#analyse)
- [Share](#share)
- [Act](#act) 

## Ask
In the "Ask" phase, I am defining the analysis scope and considering the key stakeholders to increase the likelihood of actionable insights that align with stakeholder expectations.
### Business Task:  
Identify key differences between casual riders and annual members, providing insights to develop targeted marketing strategies that convert casual riders into annual member.
### Key stakeholders:  
* **Lily Moreno**: The director of marketing, responsible for marketing strategies development.
* **Cyclist Marketing Analytics Team**: The team of data analysts, who collect, analyse, and report data to guide marketing strategy.
* **Cyclistic Executive Team**: The decision-makers who will approve or reject the recommended marketing strategies based on the analysis.
  
## Prepare
In the "Prepare" phase, I focus on preparing data for analysis through data collection, storing, organising, sort and filtering. I assess the quality of data using the ROCCC criteria, ensuring it is reliable, origial, comprehensive, current and cited to minimise the risk of error during analysis.
### Data sources:
The data is The data has been made publicly available by Motivate International Inc. under a data license agreement. 
### Inspect the data using posit cloud:
Upload files into cloud directory. Go to the targeted directory using `getwd()` and `setwd()` and read the data, including other necessary packages
```{r}
install.packages("readr")
library(readr)
setwd("/cloud/project/2023_Oct_to_2024_Sept")
df202409 <- read.csv("202409-divvy-tripdata.csv")
str(df20240)
```

### Data organisation
The data is strcutured as a data frame. Each row in the dataset is uniquely identified by an ID, representing a unit of observation for individual trips. The data is segmented into different files corresponding to each month. The data includes following columns: "ride_id," "rideable_type," "started_at," "ended_at," "start_station_name," "start_station_id," "end_station_name," "end_station_id," "start_lat," "start_lng," "end_lat," "end_lng," and "member_casual."
### Quality of data:
This dataset is reliable as it comprises internal data generated directly from the company’s operations, ensuring its originality. It is comprehensive, including detailed information about trips of the two targeted customer groups. Furthermore, the dataset is current, reflecting data collected over the past few year. Lastly, the original source of the data is formally referenced on the company’s website, ensuring proper citation.

## Process
## Analyse
## Share
## Act
