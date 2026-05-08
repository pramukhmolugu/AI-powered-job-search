# SQL Analytics Showcase

This repository demonstrates practical SQL work for an AI-powered job search product. The examples model applications, companies, job postings, recruiter touchpoints, and interview outcomes so the project can answer product and operations questions with repeatable SQL.

## What is included

- `sql/schema.sql`: PostgreSQL schema with relational constraints and analytical indexes.
- `sql/analytics_queries.sql`: business-facing analysis queries for funnel health, response rates, stale applications, and market insights.
- `sql/data_quality_checks.sql`: checks that catch duplicate postings, broken application state, missing timestamps, and inconsistent interview data.

## SQL themes demonstrated

- Normalized relational modeling
- Common table expressions
- Window functions
- Conditional aggregation
- Date bucketing and aging logic
- Data quality validation
- Index design for common filters and joins

## Suggested review focus

Reviewers should pay attention to whether the schema captures the job-search workflow clearly, whether the analytics queries answer useful questions, and whether the data quality checks would catch mistakes before dashboards or automation use the data.
