# data-engineer-101

- [data-engineer-101](https://www.udemy.com/course/data-engineering-101-the-beginners-guide/learn/lecture/43190218#overview)



- Intros
    - Data engineering covers many topics
        - ETL
        - Storage
        - Data modeling
        - Data pipeline architectures
        - and etc...
    - many tools
        - <img src="./imgs/Xnip2025-03-31_15-09-54.jpg" alt="img" width="500" />

- Section 1: what is data engineering?
    - <img src="./imgs/Xnip2025-03-31_15-12-10.jpg" alt="img" width="500" />

- Section 2: Data pipeline in-depth
    - Generation of data
        - <img src="./imgs/Xnip2025-03-31_15-13-00.jpg" alt="img" width="500" />
    - Storage
        - Types of storage systems
            - e.g. File storage vs object storage
        - Row-based storage vs columnar storage
        - data warehouse vs data lakehouse
        - right type of storage can have a performance difference of up to 100x

    - Ingestion
        - Batch vs streaming ingestion
        - ETL vs ELT
        - different ways to ingest data from different source systems

    - Transformation
        - SQL queries
        - Data modeling
        - Normalization

    - Serving
        - Data analysts
        - Data scientists
        - Reverse ETL

- Section 3: Shared components that underlie our entire data pipeline
    - Shared components
        - DataOps
        - Orchestration
        - Security
        - Data quality
        - Data privacy


- Section 4: Actual exmaples of data architectures for different use cases
    - examples of data architectures
        - Business analytics use case
        - Streaming use case
        - ML use case
        - Deep Learning use case

<br><br><br>

# Section 1 - Intros

<br>

## 1.1 What is data engineering?
1. what is data engineering
    - <img src="./imgs/Xnip2025-03-31_16-28-26.jpg" alt="img" width="500" />
    - <img src="./imgs/Xnip2025-03-31_16-29-57.jpg" alt="img" width="500" />

2. Many producers and consumers
    - <img src="./imgs/Xnip2025-03-31_16-30-52.jpg" alt="img" width="500" />

3. example - Business analytics (or BI)
    - <img src="./imgs/Xnip2025-03-31_20-44-19.jpg" alt="img" width="500" />

4. example - real time
    - <img src="./imgs/Xnip2025-03-31_20-54-29.jpg" alt="img" width="500" />

5. example - ML
    - <img src="./imgs/Xnip2025-03-31_21-00-19.jpg" alt="img" width="500" />

6. example - AI
    - <img src="./imgs/Xnip2025-03-31_21-03-18.jpg" alt="img" width="500" />

7. Why it is important?
    - explosion of data sources
        - <img src="./imgs/Xnip2025-03-31_21-06-37.jpg" alt="img" width="500" />
    - explosion of data uses
        - <img src="./imgs/Xnip2025-03-31_21-08-32.jpg" alt="img" width="500" />


<br>

## 1.2 overall architecture of end-to-end data pipeline
- E2E pipeline
    - <img src="./imgs/Xnip2025-03-31_21-22-15.jpg" alt="img" width="500" />
    - <img src="./imgs/Xnip2025-03-31_21-31-05.jpg" alt="img" width="500" />
    - <img src="./imgs/Xnip2025-03-31_21-33-33.jpg" alt="img" width="500" />

- Compute vs Storage
    - <img src="./imgs/Xnip2025-03-31_21-41-08.jpg" alt="img" width="500" />

- Undercurrents
    - <img src="./imgs/Xnip2025-03-31_21-42-36.jpg" alt="img" width="500" />

<br>

## 1.3 Some historical context
1. 1980-2000: Data warehouse
    - <img src="./imgs/Xnip2025-03-31_21-58-13.jpg" alt="img" width="500" />

2. 2000s: the beginning of "Big data"
    - S3 - distributed storage
    - EC2 - distributed processing
    - <img src="./imgs/Xnip2025-03-31_22-00-14.jpg" alt="img" width="500" />

3. 2000s - 2010s: Big data engineering
    - <img src="./imgs/Xnip2025-03-31_22-07-33.jpg" alt="img" width="500" />

4. 2020s: Modern Data Stack
    - Trend of Modern Data Stack: Hiding away the gory details of low-level concerns that plagued big data era techniques like Hadoop => Simplify data engineering
    - <img src="./imgs/Xnip2025-03-31_22-09-09.jpg" alt="img" width="500" />

<br>

## 1.4 Data maturity
- <img src="./imgs/Xnip2025-03-31_22-17-44.jpg" alt="img" width="500" />

<br>

## 1.5 Data engineer's place within a data team 
- Data engineer's place within a data team
    - Data scientist -> looking opportunities for future
    - Data analyst -> looking for insights from past data
    - <img src="./imgs/Xnip2025-03-31_22-24-32.jpg" alt="img" width="500" />

- responsibilities - business & technical
    - <img src="./imgs/Xnip2025-03-31_22-26-35.jpg" alt="img" width="500" />

- Required technical skills
    - <img src="./imgs/Xnip2025-03-31_22-28-12.jpg" alt="img" width="500" />




<br><br><br>



# Translation
SKU - Stock Keeping Unit
IoT - Internet of Things, physical objects, like appliances, vehicles, and wearables, embedded with sensors, software, and connectivity to collect and exchange data over the internet, enabling remote monitoring, control, and automation
data maturity - 数据成熟度
