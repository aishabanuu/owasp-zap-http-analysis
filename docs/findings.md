# Findings

## Request Analysis

HTTP requests were successfully intercepted through OWASP ZAP.

Observed request headers included:

- Host
- User-Agent
- Accept
- Accept-Language
- Connection

## Response Analysis

HTTP responses contained:

- Status Codes
- Content-Type
- Content-Length
- Server Information
- Set-Cookie Headers

## Cookie Inspection

Session cookies were identified and analyzed.

Examples:

- ASP.NET_SessionId
- Session Tokens

Observed attributes:

- Secure
- HttpOnly
- SameSite

## Authentication Analysis

A vulnerable training application was used to observe authentication requests.

A POST request submitted login parameters to the server.

Findings:

- Credentials were transmitted within the request payload.
- The server issued a session cookie after authentication.
- Subsequent requests used the session identifier rather than resubmitting credentials.

For ethical and security reasons, credential values displayed in screenshots have been redacted.

## Skills Demonstrated

- HTTP/HTTPS Protocol Analysis
- Proxy Configuration
- Request Interception
- Header Analysis
- Cookie Inspection
- Session Management
- Authentication Mechanisms
