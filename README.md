# udagram-reverse-proxy
NGINX Reverse-Proxy for Udagram Kubernetes Project of Udacitys Cloud Developer Nanodegree Programm. 

## About Project

The Project is built in four parts: 
* This Reverse Proxy (handling api calls to respective server)
* [Frontend Application](https://github.com/willsamu/udagram-frontend)
* [Feed](https://github.com/willsamu/udagram-feed) and [User](https://github.com/willsamu/udagram-user) Express Server which are linked to an PostgreSQL Database hostet on AWS RDS.

CI has been built using Travis, Deployment with Kubernetes has been handled with AWS. 

Screenshots can be found in the [screenshot](https://github.com/willsamu/udagram-reverse-proxy/tree/master/Screenshots) folder.
