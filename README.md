# apigee-notes
This repository is documentation of Apigee 

## Local Setup

For exploring Apigee we are going to create Micro services in local machine and going to expose those services as API's using Apigee X.
For this we need to expose our MS urls to internet which can be done using ngrok.


## ngrok setup
https://dashboard.ngrok.com/get-started/setup

Once ngrok is setup create a sample spring boot app and run it in local and expose it to internet using ngrok.

To run ngrok in local machine with basic auth use following command

ngrok http 8080 --basic-auth '<username>:<password>'

Once its started successfully we can see following log.

Forwarding     https://821b-65-27-244-128.ngrok.io -> http://localhost:8080

Everytime when we retsrt the ngrok https://<host-name> will change for each restarts.

## Apigee Introduction
https://www.youtube.com/watch?v=vGe38icp0n4

## Apigee X free account setup

It requires Google Cloud Account to be created.

https://cloud.google.com/apigee/docs/api-platform/get-started/eval-orgs

## Apigee X tutorial

https://www.youtube.com/watch?v=1hJ3S5O22KI







