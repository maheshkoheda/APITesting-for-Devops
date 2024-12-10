# API Basics and Usage

## Overview
This README provides foundational knowledge about APIs, their types, usage, and practical examples. It also includes resources and tools to practice using public APIs.

---

## What are APIs?
Application Programming Interfaces (APIs) are sets of rules and protocols enabling communication between software applications. They define how requests and responses are structured, facilitating seamless integration between systems.

---

## Types of APIs
- Open APIs (Public APIs): Accessible by any developer.
- Internal APIs: Used within an organization to streamline processes.
- Partner APIs: Shared externally with selected business partners.
- Composite APIs: Combine multiple APIs to perform sequences of related tasks.

---

## RESTful APIs
Representational State Transfer (REST) is an architectural style for designing networked applications. RESTful APIs use HTTP requests to perform standard operations:
- Create: POST
- Read: GET
- Update: PUT or PATCH
- Delete: DELETE

---

## Types of Requests in RESTful APIs
- GET: Retrieve data from the server.
- POST: Send data to create a resource.
- PUT: Update an existing resource.
- PATCH: Modify part of a resource.
- DELETE: Remove a resource.

---

## Types of Responses
API responses are typically formatted as:
- JSON (JavaScript Object Notation): Lightweight and easy to read.
- XML (Extensible Markup Language): Verbose and less commonly used in modern APIs.

### HTTP Status Codes
- 200 OK: Successful request.
- 201 Created: Resource successfully created.
- 400 Bad Request: Invalid request.
- 401 Unauthorized: Authentication required.
- 404 Not Found: Resource not found.
- 500 Internal Server Error: Server encountered an issue.

---

## URI vs. URL
- URI (Uniform Resource Identifier): A generic identifier for resources.
  - Example: `urn:isbn:0451450523`
- URL (Uniform Resource Locator): A specific type of URI with the means to locate the resource.
  - Example: `https://api.example.com/v1/resource`

### Key Difference
All URLs are URIs, but not all URIs are URLs.

---

## Advantages of REST APIs
- Scalability: Handles high traffic efficiently with stateless architecture.
- Flexibility: Supports multiple data formats like JSON and XML.
- Interoperability: Compatible with various platforms and languages.
- Simplified Communication: Decouples client and server components.
- Wide Adoption: Popular in modern web and mobile applications.

---

## Why APIs are Used in Organizations
APIs enhance functionality by enabling internal systems and external services to communicate. Examples:

### E-commerce Application
- Third-party Payment Gateways: APIs like Stripe or PayPal enable secure transactions.
- Shipping APIs: Integration with FedEx or UPS provides real-time shipping updates.

### Food Delivery Application
- Map APIs: Google Maps API supports location tracking and route optimization.
- SMS/Notification APIs: Twilio or Firebase sends order updates.
- Payment APIs: Enable secure online payments.

---

## Free Resources for Public APIs
- [RESTful API Examples](https://restful-api.dev)
- [RapidAPI Marketplace](https://rapidapi.com)

---

## Tools and Practice
- Install POSTMAN, a robust API client for testing APIs.
- Use the attached Excel document to explore and practice with publicly available APIs in POSTMAN.

---

Start exploring APIs and unlock new capabilities for your projects!

