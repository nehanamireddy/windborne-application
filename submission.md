# WindBorne Systems — Application Challenge

## 1. Tell us about a problem you couldn’t leave alone. What did you build to fix it?

At the University of Houston, I noticed that reviewing student submissions involved a lot of repetitive manual checking. With 250+ students, identifying missing, duplicate, or very similar submissions was time-consuming.

I built an AI-assisted validation pipeline using Python, Pandas, NLP embeddings, and cosine similarity. It processed assignment data and flagged submissions that needed attention instead of requiring everything to be manually reviewed.

The challenging part was determining what should actually be flagged. Simple text matching was not enough because differently written submissions could have similar meaning. I used semantic similarity to identify those cases while leaving the final decision to the instructor.

The pipeline reduced manual grading checks by about 75% and made the review process more consistent.


## 2. Tell us about a time you had to understand an unfamiliar system that wasn’t behaving as expected.

At Experian, I worked with AWS-based Apache Airflow pipelines that were experiencing recurring deployment failures. The system was initially unfamiliar to me, so I started by understanding the pipeline flow and examining Airflow logs, DAG behavior, and deployment configurations.

I compared successful and failed runs to identify patterns and traced dependencies between the different components. This helped me narrow down where failures were occurring instead of making changes based on assumptions.

After identifying the recurring issues, I made the necessary changes and monitored subsequent runs to verify the results.

The changes reduced the pipeline failure rate by 40% and improved DAG success to about 90%.

That experience reinforced my approach to unfamiliar systems is understanding the architecture, use logs and data to narrow the problem, make a targeted change, and verify the result.


## 3. Describe a real coding task where AI tools helped you move faster.

At Hyderabad Rock Sand, I used ChatGPT during a software-engineering task involving code review and debugging. I used it to quickly explore potential edge cases, identify areas that might contain bugs, and generate ideas for testing.

I did not treat its suggestions as solutions. I reviewed the existing Java/Spring Boot code, determined whether the suggestions actually matched the application's behavior, and tested the changes using JUnit and Mockito.

The biggest benefit was speed, the AI helped me explore possibilities faster, while I remained responsible for understanding the system and deciding which changes were appropriate.

At Experian, I also used Microsoft Copilot and Claude to accelerate technical documentation and requirements summarization. I reviewed and corrected the generated output before using it.

For me, AI is most useful as an accelerator, not a replacement for engineering judgment.


## 4. Describe the extent to which you have experience with production systems.

My production experience is primarily with internal enterprise applications, data workflows, and cloud-based systems.

At Hyderabad Rock Sand, I maintained a Java/Spring Boot application processing 10,000+ records, investigated production bugs, improved test coverage, and analyzed memory issues using stack traces and heap dumps.

At Experian, I worked with Python data workflows, SQL, AWS Airflow, and CI/CD, including investigating recurring pipeline failures and improving reliability.

At FedEx, I worked on a Python/FastAPI backend processing 1,000+ records and used AWS EC2, Datadog, CI/CD, and monitoring to troubleshoot application and deployment issues.

These experiences gave me practical exposure to production concerns such as monitoring, debugging, testing, data quality, failure recovery, and making changes to existing systems safely.


## 5. How many years of relevant experience do you have?

I have about 4 years of relevant experience across software engineering, data systems, and machine learning.

This includes about two years developing enterprise software at Hyderabad Rock Sand, followed by experience at Experian working with Python, SQL, Airflow, and data workflows, and a software engineering internship at FedEx involving Python, FastAPI, SQL, AWS, monitoring, and CI/CD.

I have also worked as an AI/ML Instructional Assistant at the University of Houston, where I built an NLP-based validation pipeline and supported machine learning projects.

My experience combines software development, data engineering, machine learning, NLP, debugging, testing, and production-oriented engineering practices.
