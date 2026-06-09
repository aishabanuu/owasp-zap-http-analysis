# HTTP Request and Response Analysis using OWASP ZAP

## Project Overview

This project demonstrates the analysis of HTTP and HTTPS communications using OWASP ZAP on Kali Linux.

The objective is to understand how web browsers and servers communicate through requests and responses, inspect cookies, analyze headers, and observe authentication and session management mechanisms.

---

## Objectives

- Configure a web proxy
- Capture HTTP and HTTPS traffic
- Intercept web requests
- Analyze request headers
- Analyze response headers
- Inspect cookies
- Study session management
- Understand authentication mechanisms

---

## Tools Used

- Kali Linux
- OWASP ZAP 2.17
- Mozilla Firefox
- VMware Fusion (Apple Silicon)

---

## Project Workflow

### 1. Proxy Configuration

Firefox was configured to route traffic through OWASP ZAP:

- Proxy Address: 127.0.0.1
- Port: 8080

### 2. HTTPS Certificate Installation

The OWASP ZAP Root CA certificate was exported and imported into Firefox to enable HTTPS traffic inspection.

### 3. Request Interception

Web requests were intercepted through OWASP ZAP and analyzed before being sent to the destination server.

### 4. Header Analysis

Request headers examined included:

- Host
- User-Agent
- Accept
- Accept-Language
- Connection

Response headers examined included:

- Content-Type
- Content-Length
- Server
- Set-Cookie

### 5. Cookie Inspection

Session cookies were inspected and analyzed for:

- Secure flag
- HttpOnly flag
- SameSite attribute
- Session identifiers

### 6. Authentication Observation

Authentication requests were captured and analyzed to observe how credentials and session tokens are transmitted.

---

## Skills Demonstrated

- HTTP/HTTPS Protocol Analysis
- Web Proxy Configuration
- Request Interception
- Header Analysis
- Cookie Inspection
- Session Management
- Authentication Analysis

---

## Screenshots

Screenshots of the configuration and analysis process are included in the screenshots directory.

---

## Conclusion

OWASP ZAP successfully demonstrated how web applications communicate using HTTP and HTTPS protocols. The project provided practical experience with request interception, response analysis, session management, and authentication mechanisms.
