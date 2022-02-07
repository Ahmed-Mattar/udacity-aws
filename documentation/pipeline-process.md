# Pipeline Process

The pipeline is setup and wired with this project github repo in circleCI

## Order of commands

1. The pipeline uses orbs to install the necesary tools like Node , AWS cli and EB cli.
2. It checks changes from the repo
3. install for front and backend
4. build for front and backend
5. lastly deploy for both front and backend

## Schema

1- Prepare environment: setup Node,npm,aws,EBcli
2- Install: Run npm install for both front-end and back-end
3- Build: Run build for front-end and back-end
4- Deploy: Deploy the front-end to s3 and the back-end to elasticbeanstalk
