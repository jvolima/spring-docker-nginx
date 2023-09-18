# Spring Boot + Docker + PostgreSQL + Nginx

In this repository I made a template to build an application using the stack on title.

## Stack
- Java 17
- Spring Boot 3.0.10
- JPA
- Hibernate
- PostgreSQL
- Nginx

## Prerequisites
- Docker
- Java

## How to use
1. Clone or install the repository
2. ```./mvnw clean package -DskipTests ``` to install the .jar of the project
3. ```docker-compose up -d``` to run the application and the database
4. ```docker ps``` to see if the app and database are running correctly

## What is Nginx
Have you ever faced the challenge of optimizing the performance of your API?

If so, Nginx may be the solution you are looking for. It is a powerful web server tool that excels in optimizing performance and efficiently managing connections. Nginx emerged with the purpose of tackling the dilemma known as "C10k", which concerns the difficulty that servers encountered when dealing with a large volume of simultaneous connections.

In addition to overcoming this hurdle, Nginx offers a number of advantages that make it a valuable choice for administrators and API developers:

- Horizontal Scalability: Nginx is highly scalable, allowing you to distribute the workload effectively across multiple servers. With this capability, it is possible to handle a large number of simultaneous requests without sacrificing performance.

- Reverse Proxy and Load Balancing: With integrated reverse proxy capabilities, Nginx can forward requests to application servers, improving load distribution and, consequently, API performance. Load balancing is also an essential feature, ensuring that servers receive a similar load of traffic.

- Efficient Cache: Nginx offers robust caching capabilities, allowing you to temporarily store static data and content. This reduces the load on application servers and speeds up response times for clients.

- TLS/SSL Offloading: By offloading SSL/TLS encryption processing to Nginx, application servers can focus on essential tasks, increasing efficiency and responsiveness.
  Connection Management: Nginx is notable for its efficiency in handling a large number of simultaneous connections. It uses an asynchronous approach, allowing the server to handle a significant volume of requests without increasing CPU load.

- Advanced Monitoring and Logging: Nginx offers powerful tools for traffic monitoring and detailed logging. This makes it easier to identify potential performance bottlenecks and implement improvements.

By adopting Nginx as part of your API infrastructure, you will be investing in a reliable and highly effective solution to optimize your server performance.