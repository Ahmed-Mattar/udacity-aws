# Udagram

This project is part of the Udacity FullStack JavaScript nanodegree it's the last project and it's aim is to use aws services to host a full stack application.

The project is available at

http://mattar-udagram.s3-website-us-east-1.amazonaws.com

## Configuration Screenshots

### proof the site is working and connected to the backend

logged in with a made email
![connected proof](./screenshots/connected.png)

### Elastic Beanstalk Environment

![Elastic Beanstalk Environment](./screenshots/screencapture-console-aws-amazon-elasticbeanstalk-home-2022-02-07-16_56_18.png)

### FrontEnd S3 Bucket

![FrontEnd S3 Bucket](./screenshots/screencapture-s3-console-aws-amazon-s3-buckets-mattar-udagram-2022-02-07-15_31_38.png)

### PostgreSQL RDS database

![PostgreSQL RDS database](./screenshots/screencapture-console-aws-amazon-rds-home-2022-02-07-14_25_43.png)

### CircleCI Pipeline

![CircleCI Pipeline](./screenshots/screencapture-app-circleci-pipelines-github-Ahmed-Mattar-udacity-aws-21-workflows-a4d58140-8bc7-459b-86f1-ecb65a39d589-jobs-21-2022-02-07-21_31_07.png)

added secrets here

![CircleCI Pipeline environment variables](./screenshots/screencapture-app-circleci-settings-project-github-Ahmed-Mattar-udacity-aws-environment-variables-2022-02-07-19_53_35.png)

## schema

1- Prepare environment: setup Node,npm,aws,EBcli
2- Install: Run npm install for both front-end and back-end
3- Build: Run build for front-end and back-end
4- Deploy: Deploy the front-end to s3 and the back-end to elasticbeanstalk

### Architecture

![Architecture](./documentation/Diagram.drawio.png)

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework
