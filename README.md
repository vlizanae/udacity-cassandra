# Data modeling with Cassandra

by Vicente Lizana

## Summary

At Sparkify, there are three new questions in the need of answers. Because of the
massive growth of the company's data, a NoSQL database was proposed, so the
analytics team can perform fast queries over denormalized data to answer these questions.

Apache Cassandra was selected for the job because of its focus in Availability and
Partition Tolerance. The distributed aspect and linear horizontal scalability are
fundamental to keep the pace of the data growth.

## How to Run

To populate the database and run the verification queries run the notebook `Project_1B.ipynb`.

## Files on the Project

- Project_1B.ipynb: For each of the three queries:
    - Small analysis of the data
    - Create the table
    - Load the data
    - Run the query to verify it is working
