Project Overview:-

-This project is a Doctor Appointment Booking System built using Spring Boot Microservices architecture. It allows patients to search doctors, book appointments, and process payments. The services communicate using REST APIs and Apache Kafka.

Technologies :-

-Java
,Spring Boot
,Spring Data JPA
,MySQL
,Apache Kafka
,Eureka Server
,OpenFeign
,REST APIs
,Maven

Microservices:-

Doctor Service – Manages doctor information such as adding and searching doctors.
Patient Service – Handles patient registration and details.
Booking Service – Responsible for creating and storing appointments.
Payment Service – Processes payments for booked appointments.
Eureka Server – Provides service discovery for all microservices.

How to Run the Project:-

-Start Zookeeper
-Start Kafka Server
-Run Eureka Server
-Run all microservices
-Test APIs using Postman
