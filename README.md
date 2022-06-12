# hardwareStoreApp
SPRING BOOT REST APLIKACIJA DEMO<br /><br />

I made a demo of spring boot web application that could be used as backend for hardware stores. <br />
Application was used to learn new concepts of Spring Boot framework so it's not perfect and finished.<br /><br />


Application:<br />
Possibility to add, delete and update hardware on store.<br />
User can make reviews on hardware compontents.<br />
User can add and delete hardware components to cart.<br />
User can order components from cart.<br />
For every object there are validations on controller level.<br />
There are different roles - ADMIN,STAFF,USER (Admin can promote or demote user and staff role)<br />
Application is used with in memory h2 database.<br />
Spring security with authentication and authorization using jwt tokens.<br /><br />

TODO:<br />
Connecting email to application for account confirmation and so users can get order details.<br />
Testing, there are few tests on controller level, but a lot more are missing.
