# Burp Suite Analysis Report

## Objective
To analyze HTTP request-response behavior using Burp Suite.

## Steps Performed
1. Visited browser through Target section
2. Intercepted request using Proxy
3. Sent request to Repeater
4. Modified Host header
5. Observed 301 redirect
6. Corrected request and got 200 OK
7. Tested POST method and got 400 error

## Tools
- Kali Linux
- VMware
- Burp Suite community edition
  
## Observations
- 301 redirect occurs due to domain redirection
- 400 occurs due to malformed request
- 200 indicates successful request
- Website uses HTTPS enforcement as HTTP is not safe

## Conclusion
This project helped to understand the HTTP protocol and real-world server behavior.
