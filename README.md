# Spring Boot Address Book Application

Welcome to the Address Book application built with Spring Boot. This project demonstrates the use of REST APIs to perform CRUD operations for managing contacts.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)

## Overview

The Address Book backend allows you to store, update, and retrieve contact information like name, address, city, state, zip code, and phone number using RESTful APIs.

## Technologies Used

- Java 17+
- Spring Boot
- Spring Web
- Lombok
- H2 Database
- Maven

## Features

- Add, update, delete, and search contacts
- Validation of user inputs using annotations
- Organized by DTOs and services
- In-memory H2 support

## Project Structure

- `model` – Contact model  
- `dto` – DTOs with validation  
- `controller` – API endpoints  
- `service` – Business logic  
- `repository` – In-memory or DB layer

## API Endpoints

- `GET /contacts` – Get all contacts  
- `GET /contacts/{id}` – Get contact by ID  
- `POST /contacts` – Add new contact  
- `PUT /contacts/{id}` – Update contact  
- `DELETE /contacts/{id}` – Delete contact  
