# Random-User-API-Performance-Test
This project contains a JMeter test plan for load testing and Stress testing the Random Data API (https://random-data-api.com/api/v2/users). The test plan includes HTTP Request samplers and assertions to validate the responses, and a set of performance metrics to measure the response times of the API.

## JMX File
The JMX file for this project is named `random-user-data-api.jmx`.
To run the test plan, you will need to have [JMeter](https://jmeter.apache.org) installed on your computer.

## Scenario:
Find out the actual TPS for if 120000 user can give load for 12 hour.

## How to Run the Test
1. Open the JMX file in JMeter.
2. Click the "Start" button to run the test.
3. Wait for the test to complete.
4. Analyze the results to determine the actual TPS (transactions per second) for the API.

## Perform load test on this URL:
https://random-data-api.com/api/v2/users

### Breakdown the expected TPS in excel sheet and find out the actual TPS:
![Loadtest](https://user-images.githubusercontent.com/52671754/215353406-3daedef0-f12b-4d92-829b-a423d6a9acca.png)

### Find out the bottleneck/stress test point:
![stress_test](https://user-images.githubusercontent.com/52671754/215774602-d52c3ba4-459e-4668-8a85-657f23a7b6b4.png)
