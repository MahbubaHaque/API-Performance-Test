# Random-User-API-Performance-Test
## Purpose of Performance Testing:
Features and Functionality supported by a software system are not the only concern. A software application’s performance, like its response time, reliability, resource usage, and scalability, do matter. The goal of Performance Testing is not to find bugs but to eliminate performance bottlenecks.

## Why Choose Apache JMeter for API Testing?

- Open-source tool - The Apache JMeter is an open-source tool based on Java used to perform load testing and performance testing.
- Cross-platform testing - Since JMeter is solely Java-based, it can be used on any platform that has a JVM; Windows, Linux, or macOS.
- Smooth API Testing - API Testing enables easy, smooth, and rapid API testing.

## Load Testing Strategy:
In load testing, I always got actual tps when I hit this https://random-data-api.com/api/v2/users server with multiple users several times in every request. The actual value is 2.7, which is close to the expected value. I did not find any errors when I hit the system.

![Load-1](https://user-images.githubusercontent.com/123467715/215416500-e7e9be3b-986e-493a-908c-f5d107b1feb2.PNG)
![load1](https://user-images.githubusercontent.com/123467715/215390403-c55a3f84-91a9-4e94-8100-88e2f11d6db1.jpg)

## Stress Testing Strategy:
When, I hit the system with 4200 users in 1200 second then, I find out the bottleneck/stress test point which is exactly 1% error.

![Stress](https://user-images.githubusercontent.com/123467715/215394905-b662a1b5-9680-422a-8948-ac30a1df6c9f.PNG)

## Solving Following Questions:
Find out the actual TPS for if 120000 user can give load for 12 hour
Perform load test on this URL: https://random-data-api.com/api/v2/users
1. Find out if the expected TPS (Transaction Per/Second) meet the above requirement.
Breakdown the expected TPS in excel sheet and find out the actual TPS.

2. Create another excel sheet where find out the bottleneck/stress test point. (At which point the system starts to show 1% error.

