# Laravel-Serverless

## A very basic skeleton in Laravel 9 which makes use of:

* Laravel
* Bref (provides php runtimes in lambda)
* Serverless Framework
* serverless-lift-plugin (to create/manage s3 buckets)
* Lambda (a FaaS (functions-as-a-service) offering from AWS)
* S3 to store and serve public/storage files.
* DynamoDB for Cache & Session storage.

## Pending Features: 

* SQS to create and work asynchronous jobs.
* SES (Simple Email Service) for outbound messages.

## Still in the Air:

* RDS & RDS Proxy. These are not serverless offerings, but a relational DB is a nice-to-have. 

## Deployment & Development

In order to deploy this project, you'll need NodeJS, Serverless Framework, and the serverless-lift-plugin.

Development should be local, using Laravel Sail for the easiest developer experience. 
