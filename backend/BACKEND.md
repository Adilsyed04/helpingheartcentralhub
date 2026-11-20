# Backend 

Plan: Implementing a Postgres Database utilizing Typescript and Prisma

Basic Flow:

A chapter lead logs in, submits an event and its items through the dashboard, the API checks it and saves it in Postgres, and the dashboard reads totals back out (people served, items given, events per chapter). Requests go from the dashboard through API Gateway to Lambda, which is the only part that talks to the database.
