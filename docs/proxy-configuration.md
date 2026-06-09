# Proxy Configuration

## OWASP ZAP Proxy Settings

Default proxy:

- Address: 127.0.0.1
- Port: 8080

Navigate to:

Tools → Options → Network → Local Servers/Proxies

## Firefox Configuration

Settings → Network Settings → Manual Proxy Configuration

Configure:

- HTTP Proxy: 127.0.0.1
- Port: 8080
- Also use this proxy for HTTPS: Enabled

## HTTPS Certificate Setup

In OWASP ZAP:

Tools → Options → Network → Server Certificates

Export the Root CA certificate.

In Firefox:

Settings → Privacy & Security → Certificates → View Certificates → Authorities → Import

Select the exported certificate and trust it for website identification.

## Verification

Visit:

https://example.com

Traffic should appear in the OWASP ZAP Sites Tree and History tab.
