# What is Airflow
Airflow is a schedular/orchesterator which helps us run our jobs in right order at right time in right manner.

## Example
suppose you have a project which does following.
1. sqoop data from Teradata
2. pre-process data
3. Create some analytics results.
4. Update dashboard

You would like these jobs to run in specific sequence and at specific time. otherwise you will not get desired result. you will also like to use specific tech for each task. when any of step fails, you would like to get notified and next jobs should get on hold. Apache airflow helps to get these things done.

