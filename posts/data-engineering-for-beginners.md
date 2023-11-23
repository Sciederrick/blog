---
title: 'Data Engineering for Beginners'
date: 2023-23-11
author: Derrick Mbarani
gravatar: f0984c32939909a82c61b68289625aa254c47bbc26ccacc4c44d4a8ff957a5d2
twitter: '@der15171'
---

This data engineering guide aims to give you a glimpse of roles and responsibilities of a data engineer with real-world scenarios in a story format.

---

You are planning to make a transition into data engineering. This guide assumes you are starting from scratch with insights gathered from various sources and also based on how I am going about it.

Clive Robert Humby OBE, a British mathematician and entrepreneur in the field of data science and customer-centric business strategies, highlighted the importance of data with his quote, “Data is the new oil.” This also highlights the importance of the designation that handles data. For an enterprise-level business, for every data scientist, there will be twice if not more Data Engineers to support them.

Imagine you own an e-commerce business. It generates vast amounts of data daily, including customer interactions, product sales, and website traffic. To harness the potential of this data, you require a data engineer to act as the backbone of your data operations.

For instance, you want to implement a recommendation system on your platform to suggest personalized products to customers. To make this happen, you rely on a data engineer to collect and process user behavior data, product inventory data, and customer profiles. They create a seamless flow of data, making it available for machine learning algorithms and data scientists to build the recommendation engine.

Now that we've seen how a data engineer's role is pivotal in implementing data-driven features like recommendation systems, let's delve into the specific roles and responsibilities that data engineers undertake to ensure the success of such projects.

## Roles and Responsibilities

Data engineering is one of the most technical roles in the field of data science, bridging the gap between software and application developers and traditional data science positions by:

- Coming up with a data strategy for the target company.

- Designing and building the infrastructure and systems that support data collection, storage, and analysis

- Managing and maintaining large data sets and databases

- Ensuring data is accurate, accessible, and secure

- Data engineer's day-to-day revolves around 2 processes:

- ETL (Extract, Transform, Load) Processes include developing data extraction, transformation, and loading tasks, and moving data between different environments.

- Data Cleaning Processes so that it arrives in a normalized and structured fashion into the hands of analysts and data scientists.

- Optimizing ML models for performance and deploying them.

The nature of these tasks is cumbersome especially when working for a data-driven enterprise. This is why data pipelines exist. Suppose a data analyst requests for data at the beginning of every week. You will create a pipeline to move data from an on-premise database to the cloud so that the Analyst will ingest it from PowerBi for visualizations. You will schedule this to occur, for instance, every Sunday morning so that the data is ready by Monday. Pipelines automate these processes making data readily available when needed. However, pipelines are not needed in every project. Only when there is lots of data from different sources.

## How To Become a Data Engineer

- You are new to the field of Computer Science. Explore CS50's course to learn the fundamentals to easily understand terminology and concepts in Data Engineering.

- Explore programming languages. I recommend Python. You’ll be writing a lot of transformation jobs, deployment scripts, validation and testing, and for that, you need to master at least one programming language.

- Learn automation and scripting on Unix. Most servers (your deployment target) use Unix-based operating systems as they are light and fast. I recommend bash scripting. For instance:

- You will be working on cloud-based servers with Linux scripts to accomplish data engineering tasks.

- Bash scripting is used to do data processing, file management, and system administration tasks. This helps data engineers to save time and focus on more complex tasks.

- You will need to do orchestration (the deployment and management of complex distributed systems), making it an incredibly useful skill.

- Learn database management and SQL.

- Learn the basics of cloud computing and adopt at least one platform between AWS, Google Cloud and Azure.

- Improve your communication skills. Data engineers need communication skills to work across departments and understand the needs of data analysts and data scientists as well as business leaders. Depending on the organization, data engineers may also need to know how to develop dashboards, reports, and other visualizations to communicate with stakeholders.

- Leverage Data Tools

**Scenario: Meet Sam, the Data Scientist**

Sam is a data scientist working at a small e-commerce startup called "Techies". The company has recently launched its online store and is eager to dive into data-driven decision-making. Sam's journey with data tools starts simply and becomes increasingly complex as the company's data and analytical needs grow.

**Beginning with Python:**

At the start, Sam deals with a manageable amount of data. He uses Python for data analysis, employing libraries like Pandas and Matplotlib to explore customer behavior, sales trends, and product preferences. Python's simplicity and versatility make it perfect for handling the initial dataset.

**Introducing Airflow for Automation:**

As Techies gains popularity, more data accumulates. Sam is now faced with repetitive data collection tasks. He discovers Apache Airflow, a data pipeline orchestration tool. Sam uses Airflow to automate the extraction of daily sales data from their database and generate daily reports for the team. This saves time and ensures data is always up-to-date.

**Scaling up with Spark, then dbt:**

Techies continues to grow rapidly, and the dataset has become too massive for Pandas to handle efficiently. Sam turns to Apache Spark, a big data processing framework. He can still use Python with PySpark, which simplifies the transition. Now, Sam can perform complex analyses on large datasets without a hitch.

With Techies expanding and demanding more complex data transformations, Sam realizes the need for a better solution. He introduces dbt (data build tool) into the data stack. dbt simplifies and automates the process of transforming raw data into a structured, analytics-ready format. Now, Sam can create reusable SQL-based transformations and models, making it easier for the data team to work with data efficiently. This addition streamlines the data engineering process, improving the overall quality and accessibility of data for the team. So, as Techies' data needs become more intricate, dbt becomes an essential tool for managing data transformations and ensuring high-quality, structured data for analytics and decision-making.

**Real-time Analytics with Kafka:**

As Techies expands globally, real-time data analysis becomes crucial. Sam adopts Apache Kafka for stream processing. This allows him to monitor website traffic, analyze customer behaviors in real time, and send personalized product recommendations to users while they're still browsing the site.

**Transition to the Cloud:**

To accommodate the growing dataset and computational needs, Sam leads Techies to transition to the cloud. They choose Microsoft Azure, a cloud framework that offers scalability, storage, and computational power. Sam seamlessly migrates their data and analytical tools to the Azure platform. This shift to the cloud streamlines operations, allowing them to focus on insights rather than infrastructure

**Data Storage Evolution: The Transition to a Data Warehouse**

As TechTrends' dataset continues to grow, they face the challenge of managing and organizing data effectively. Sam recognizes the need for a more robust data storage solution. While they initially relied on a combination of file storage and databases, it's time to step up.

To address this, Sam leads the adoption of a data warehouse. A data warehouse provides a structured and optimized storage solution for analytical queries, improving the performance of data retrieval. He chose Snowflake, a cloud-based data warehousing platform known for its scalability and performance.

Sam and the team started migrating data from various sources into Snowflake. This transition offers a centralized repository for structured data, making it easier to perform complex analytics and maintain data consistency. It also complements their decision to move to the cloud, aligning data storage with their cloud infrastructure.

This shift is essential for data governance, as it enhances data quality, ensures data is easily accessible, and simplifies the data transformation process with dbt.

So, as Techies' data needs grew more intricate, dbt became an essential tool for managing data transformations and ensuring high-quality, structured data for analytics and decision-making. The transition to Snowflake as a data warehouse was the next logical step to handle the increasing dataset and improve data management, maintaining the company's focus on effective data-driven decisions.

**AI-Driven Solutions**

As TechTrends continues to thrive, they plan to implement AI-driven chatbots and recommendation engines. Sam recognizes the need for more advanced tools and explores machine learning models, using sci-kit-learn for development. He scouts for a data scientist to complement his efforts.

The cloud infrastructure provides the ideal environment for deploying and scaling these AI models, allowing Techies to provide personalized customer experiences.

In this journey, Sam's transition to the cloud was vital for accommodating the growing dataset and analytical needs, ensuring that Techies could effectively harness data and make data-driven decisions.

## Another perspective for structured, semi-structured and structured data

For Techies, an e-commerce platform, the choice between a data warehouse, data lake, and data mart depends on the specific data needs and business objectives. Each data storage approach serves different purposes, and the decision should align with the company's goals and evolving data requirements. Here's a qualified choice for each of these options:

- Data Warehouse (Cloud-based Data Warehouse like Snowflake):

Use Case: Techies should consider a data warehouse when they require a structured, centralized repository for their transactional data, customer information, sales, and order history. A data warehouse is ideal for structured data that needs to be efficiently queried and analyzed.

Justification: Given the e-commerce nature of Techies, they deal with structured transactional data, such as customer profiles, purchase histories, and product information. This data often needs to be aggregated and analyzed for business intelligence, reporting, and decision-making. A cloud-based data warehouse like Snowflake can provide scalable storage and powerful querying capabilities to meet these needs.

- Data Lake (Azure Data Lake Storage):

Use Case: A data lake is suitable for Techies when they have diverse, unstructured or semi-structured data sources, such as weblogs, customer reviews, social media data, and sensor data. Techies can benefit from a data lake when they want to store raw data for exploratory analysis and future use.

Justification: As Techies expands globally, they may encounter a variety of data types, including unstructured or semi-structured data like customer reviews, user-generated content, and social media data. Storing this data in a data lake (e.g., Azure Data Lake Storage) allows for flexible data storage and retrieval, enabling advanced analytics, machine learning, and future data-driven initiatives.

- Data Mart (Business Analytics Data Mart):

Use Case: Techies can leverage data marts when specific departments or teams, such as marketing or sales, require tailored and highly optimized data subsets for their analytics and reporting needs.

Justification: Within Techies, individual departments, like the marketing team or sales department, may need specialized data marts to cater to their specific analytical requirements. Data marts can act as focused, subject-specific data repositories, which can be derived from the central data warehouse or data lake. These data marts provide teams with quicker access to the data they need for targeted analytics and decision-making.

## Summary

Now you know what data engineering is all about and how to go about it with the tools at hand. I hope "Techies" journey has given you a sneak peak of life as a data engineer. Follow Sam's example, and use only what you need in the context of time. Additionally, do project-based learning and explore relevant case studies. Please comment if you find/have a great source for these (data engineering case studies).

## References

- [How to become a data engineer](https://www.datacamp.com/blog/how-to-become-a-data-engineer)

- [Top 10 analytics careers](https://www.datacamp.com/blog/top-ten-analytics-careers)

- [How to become a data engineer](https://www.projectpro.io/article/how-to-become-a-data-engineer/588)

- [Roadmap for data engineering](https://medium.com/@darshilp/roadmap-for-data-engineering-2023-13f62f85d866)