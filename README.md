# SkyRush

SkyRush is an innovative flight reservation system that revolutionizes the way users search for and book flights. Built as a final project for SOA, this system leverages Java, Spring Boot, and SOAP-based web services to provide a robust, secure, and scalable platform for managing flight data and reservations.

## Features

- **SOAP Web Services:** Built using Spring Web Services, all functionalities are exposed as SOAP endpoints, ensuring standardized communication and seamless integration.
- **Flight Management:** Retrieve and manage detailed flight information such as flight number, departure and destination cities, schedule, and pricing.
- **MySQL Database:** Uses MySQL for persistent storage, with Flyway managing versioned database migrations to ensure smooth updates.
- **Modular Architecture:** Organized into clearly defined layers (configuration, endpoints, models, repositories, services, and SOAP DTOs) for easy maintenance and extensibility.
- **Secure & Scalable:** Designed with high security and scalability in mind, making it ready for integration with advanced authentication and authorization mechanisms.

## Tech Stack

- **Java** with **Spring Boot** for backend development.
- **Spring Web Services** for implementing SOAP endpoints.
- **MySQL** as the primary database.
- **Flyway** for managing database migrations.
- **Maven** for dependency management and build automation.

## Project Structure

flight-reservation-soap/ ├── pom.xml ├── src │ ├── main │ │ ├── java │ │ │ └── com │ │ │ └── example │ │ │ └── flightreservation │ │ │ ├── FlightReservationApplication.java │ │ │ ├── config │ │ │ │ └── WebServiceConfig.java │ │ │ ├── endpoint │ │ │ │ └── FlightEndpoint.java │ │ │ ├── model │ │ │ │ └── Flight.java │ │ │ ├── repository │ │ │ │ └── FlightRepository.java │ │ │ ├── service │ │ │ │ └── FlightService.java │ │ │ └── soap │ │ │ ├── GetFlightRequest.java │ │ │ └── GetFlightResponse.java │ │ └── resources │ │ ├── application.properties │ │ ├── flight.xsd │ │ └── db │ │ └── migration │ │ └── V1__Initial_setup.sql └── README.md




## Getting Started

### Prerequisites

- **Java 11** or later
- **Maven 3.x**
- **MySQL Server** (create a database named `flightdb`)
- An IDE (e.g., IntelliJ IDEA, Eclipse)

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/B1udger/SOA-A---Final-Project.git
   cd SOA-A---Final-Project
