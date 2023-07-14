---
puppeteer:
  headerTemplate: |
    <html>
      <div style="display:flex; width:100%; margin: 0 10px;">
        <div style="flex:1">
          <div style="font-size:6px;color:#eeeeee">Document Number</div>
          <div style="font-size:8px">FT-1308-1</div>
        </div>
        <div style="flex:1;text-align:center">
          <div style="font-size:6px; color:#eeeeee">Document Title</div>
          <div style="font-size:8px">Software Requirement</div>
        </div>
        <div style="flex:1;text-align:right">
          <div style="font-size:6px; color:#eeeeee">Revision</div>
          <div style="font-size:8px">1.0</div>
        </div>
      </div>
    </html>
  footerTemplate: |
    <html>
      <div style="width:100%; text-align:Center; border-top: 1pt solid #eeeeee; margin: 0 20px -10px 0; font-size: 8pt; color: #000000">
        CONFIDENTIAL
      </div>
    </html>
  displayHeaderFooter: true
  margin:
    top: "15mm"
    bottom: "15mm"
Document Number: FT-1308-1
---

# Software Engineering<br/>Software Requirements Specification (SRS) Document

## SOUP information

- Package Name: [Express.js](https://github.com/expressjs/express)
- Programming Language: JavaScript & TypeScript
- Version: 4.18.1
- Verified date: 03/01/2023

## Revisions

| Version | Primary Author(s) | Description of Version | Date completed |
| :-----: | ----------------- | ---------------------- | -------------- |
|   1.0   |    Tinh Tran      |                        | 03/01/2023     |
|         |                   |                        |                |
|         |                   |                        |                |

## Review & Approval

### Requirement Document Approval History

| Approving Party | Vesion Approved | Signature | Date       |
| :-------------: | :-------------: | --------- | ---------- |
|     ITR VN      |       1.0       |           | 03/08/2023 |
|                 |                 |           |            |
|                 |                 |           |            |

### Requirement Document Review History

| Approving Party | Vesion Approved | Signature | Date       |
| :-------------: | :-------------: | --------- | ---------- |
|  Thang Nguyen   |       1.0       |           | 03/03/2023 |
|                 |                 |           |            |
|                 |                 |           |            |

<!-- pagebreak -->

## 1. Introduction

The Software Requirements document outlines the functional and non-functional requirements for the development and implementation of the software using Mongoose.js. This document serves as a guide for the design, development, and testing phases of the software project.

### 1.1. Purpose

The purpose of this document is to define the software requirements and specifications that must be met for the successful implementation of the software solution. It provides a clear understanding of the desired functionalities, performance expectations, and quality attributes of the software.

### 1.2. Document conventions

In this document, the following conventions are used:

- "Shall" indicates a mandatory requirement.
- "Should" indicates a recommended or desirable requirement.
- [Specify any other document conventions or symbols used for requirements representation.]

### 1.3. Intended audience

This document is intended for the backend development team and validation processes.

### 1.4. Scope

The scope of this document encompasses the software system developed using Express.js. It includes both functional and non-functional requirements necessary for the successful development and deployment of the software.

### 1.5. References

This document references to the following documents

- [Express.js Document](https://expressjs.com/)

## 2. General description

### 2.1. Product perspective

- Express.js provides a lightweight and flexible environment for building web applications and APIs. It is designed to work in conjunction with Node.js, utilizing its event-driven, non-blocking I/O model.

### 2.2. Product features

The key features of Express.js include:

- Routing: Express.js enables easy and flexible routing of requests to different endpoints based on URL patterns and HTTP methods.
- Middleware: Express.js offers a middleware architecture that allows developers to add functionality and modify requests and responses in a modular way.
- Template Engines: Express.js supports various template engines, such as EJS and Pug, to dynamically generate HTML and render views.
- Error Handling: Express.js provides built-in error handling mechanisms to handle and respond to errors gracefully.
- Session Management: Express.js supports session management and provides mechanisms for storing session data.
- JSON Web Tokens (JWT): Express.js allows for easy integration with JWT-based authentication and authorization systems.

### 2.3. User classes and characteristics

The Express.js framework is designed for developers who are familiar with JavaScript and want to build web applications and APIs using Node.js. The user classes and their characteristics include:

- Full-stack Developers: Experienced developers with knowledge of server-side and client-side development who can leverage Express.js to build end-to-end web applications.
- API Developers: Developers focused on building RESTful APIs using Express.js to handle request routing, middleware, and response generation.

### 2.4. Operating environment

Express.js is compatible with Linux OS.

### 2.5 Constraints

The development and usage of Express.js are subject to the following constraints:

- Node.js Dependency: Express.js relies on Node.js as its runtime environment and requires the installation of Node.js to run applications built with Express.js.
- JavaScript Language: Express.js is primarily used with JavaScript, and developers need to have a good understanding of the language.

### 2.6. Assumptions and dependencies

The development and operation of Express.js-based applications assume the following:

- Basic JavaScript Knowledge: Developers using Express.js are assumed to have a fundamental understanding of JavaScript programming.
- Availability of Node.js: Express.js relies on the Node.js runtime, and its usage assumes that Node.js is installed and available in the development and deployment environments.
- External Dependencies: Express.js applications may depend on additional Node.js modules and libraries, as determined by the specific requirements of the application.

## 3. System requirements

### 3.1. Functional requirements

- Implement robust and flexible routing mechanisms for handling incoming HTTP requests.
- Support middleware integration for adding custom functionality to the request/response cycle.
- Provide seamless integration with templates engines for dynamic content generation.
- Implement reliable error handling mechanisms for capturing and reporting exceptions.
- Support integration with databases through various database drivers or ORMs.

## 4. External interface requirements

### 4.1. User interfaces

The software should provide intuitive and user-friendly interfaces for managing and interacting with the web application or API.

### 4.2. Hardware interfaces

None applied.

### 4.3. Communications interfaces

The software should support standard communication protocols, such as HTTP or WebSocket, for interaction with clients and other systems.

### 4.4. Software interfaces

The software is built on top of Node.js and relies on the Express.js framework as a primary software interface.

## 5. Non-functional requirements

### 5.1. Performance requirements

The software should exhibit efficient response times and handle concurrent requests effectively to ensure optimal performance.

### 5.2. Safety requirements

The software should implement security best practices to protect against common web application vulnerabilities and ensure the integrity of user data.

### 5.3. Security requirements

The software should support secure communication protocols, implement access control mechanisms, and handle authentication and authorization securely.

### 5.4. Software quality attributes

The software should exhibit high reliability, maintainability, scalability, and extensibility to accommodate potential future updates and enhancements.

### 5.5. Other requirements

None applied.