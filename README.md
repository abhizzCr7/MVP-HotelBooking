# MVP-HotelBooking
Assessment for HRS


## Overview

This is a Spring Boot application for managing hotel bookings. The application allows users to search, create, update, view, and cancel hotel bookings. It integrates with PostgreSQL for data persistence and uses Prometheus for metrics collection.

## Getting Started

The application exposes all actuator endpoints, which can be accessed at http://localhost:8080/actuator.

## Metrics and Monitoring

The application uses Micrometer with Prometheus for metrics collection. To access the Prometheus metrics
http://localhost:8080/actuator/prometheus

## Test Classes
BookingControllerTest: Tests for BookingController
HotelControllerTest: Tests for HotelController

## Script for additional data

generate_test_data.sql is present under the src/main/resources directory:
