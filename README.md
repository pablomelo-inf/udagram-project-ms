# Udagram Image Filtering Application(Microsservices)

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

The project is split into two parts:
1. Frontend - Angular web application built with Ionic Framework
2. Backend RESTful API - Node-Express application


Microservices structure in EKS:

-backend-feed        
-backend-user         
           
-publicfrontend       
-publicreverseproxy 
                                                           
-udagram-frontend

-reverseproxy 

