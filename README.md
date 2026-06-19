# Burp Suite Web Analysis Report

 Objective:
To analyze and manipulate HTTP requests and responses using Burp Suite.

## Methodology
- Intercepted traffic using Burp Proxy
- Sent requests to Repeater
- Modified headers and methods
- Observed server responses

## Results

 Test Case 1: Redirection
- Input: trip.com
- Output: 301 redirect to ctrip.com

 Test Case 2: Invalid Request
- Modified Host header incorrectly
- Result: 400 Bad Request

 Test Case 3: Valid Request
- Correct Host header
- Result: 200 OK

 Test Case 4: Method Change
- GET → POST
- Result: 400 Bad Request (missing body)



## Conclusion
The experiment demonstrated how web servers handle different request types and how modern applications rely on frontend routing mechanisms.
