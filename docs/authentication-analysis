## Authentication Request Analysis

A login request was intercepted using OWASP ZAP on a deliberately vulnerable training application.

The captured POST request contained authentication parameters submitted by the user. For security and ethical reasons, any credential values shown in this repository have been redacted.

### Findings

- Credentials were transmitted in the login request payload.
- Authentication occurred via an HTTP POST request.
- The server returned a session cookie after successful authentication.
- Subsequent requests used the session identifier rather than resending credentials.
