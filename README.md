# hardwareStoreApp
SPRING BOOT REST APLIKACIJA DEMO

I made a demo of spring boot web application that could be used as backend for hardware stores. 
Application was used to learn new concepts of Spring Boot framework so it's not perfect and finished.


Application:
Possibility to add, delete and update hardware on store.
User can make reviews on hardware compontents.
User can add and delete hardware components to cart.
User can order components from cart.
For every object there are validations on controller level.
There are different roles - ADMIN,STAFF,USER (Admin can promote or demote user and staff role)
Application is used with in memory h2 database.
Spring security with authentication and authorization using jwt tokens.

TODO:
Connecting email to application for account confirmation and so users can get order details.
Testing, there are few tests on controller level, but a lot more are missing.
