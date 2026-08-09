# 🔌 ElderCare Connect — API Testing

## 📌 Overview

This folder contains API testing documentation for the **ElderCare Connect** web application.

The API testing activities focus on validating REST API endpoints, request and response behavior, authentication, authorization, input validation, and data returned by the backend services.

---

## 🎯 Testing Objectives

The main objectives of API testing are to:

- Verify API endpoints return the expected responses
- Validate HTTP status codes
- Verify request and response data
- Test authentication and authorization
- Validate role-based access control (RBAC)
- Test valid and invalid request data
- Verify error handling
- Check API behavior for unauthorized requests
- Validate JSON response structure

---

## 🧪 Application API

ElderCare Connect uses a REST-based backend built with:

- Node.js
- Express.js
- MongoDB
- JWT Authentication

The application API is organized into major route groups such as:

```text
/api/auth
/api/residents
/api/reports
/api/admin
