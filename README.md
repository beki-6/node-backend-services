# node-backend-services
Backend microservices for Woreda Management System(WMS)

These are backend services for a Woreda(kebele) management system. It involves individual services that are loosely coupled with a Database per Service pattern and an API gateway that acts as a proxy for the backend services. Communications between the services are implemented by using the Publisher/Subscriber (pub-sub) pattern using Redis. It is an asynchronous communication which is non-blocking which is better that ordinary HTTP communication as used in REST APIs. 
