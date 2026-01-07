# CODTECH Internship – Task 4  
## Advanced Load Testing Using Gatling

*Company:*CODTECH IT SOLUTIONS

*Intern Name:*Kandimalla Niharika

*Intern id:*CTIS2057

*Domain:*Software Testing

*Duration:*4 weeks

*Mentor:*Neela Santosh

PROJECT TITLE:LOAD TESTING WITH GATLING

## Objective
To perform advanced load testing on a web application using Gatling and analyze system performance under simulated heavy loads.

## Tool Used
- Gatling (Scala-based load testing tool)
- Java JDK

## Application Tested
- URL: https://jsonplaceholder.typicode.com
- Endpoint: /users
- Type: Public demo REST API

## Test Scenario
- Simulated 100 concurrent users
- Ramp-up time: 30 seconds
- Each user sends HTTP GET requests to the /users endpoint

## Test Script
The load test was written using Gatling DSL in Scala.
The script simulates multiple users accessing the API simultaneously to measure performance.

## Performance Metrics Analyzed
- Response Time (Minimum, Maximum, Average)
- Requests per Second
- Successful vs Failed Requests
- Load distribution over time

## Results Summary
- The system handled concurrent users successfully.
- No request failures observed.
- Response times remained within acceptable limits.
- Performance remained stable under heavy load.

## Conclusion
Gatling successfully simulated high traffic on the application.
The tested API demonstrated good performance and stability under load.

## Deliverables
- Gatling simulation script
- Load testing report (HTML)
- Documentation of test results
