# What is backend?

Backend is actually the server side and the backbone of any web application. Backend is responsible for the server, application and database that work together to make sure front end works as it should.

Backend is mainly responsible for:

  1. Database interaction: Handling the storage, retrieval and management of data. This involves querying databases to fetch information or update records based on user interaction or system requirements.
  2. Server logic: Executing the server-side scripts and managing application workflows. It ensures that the right processes are executed at the right time, based on user action or scheduled tasks.
  3. Application workflows: Ensuring the smooth operation of the application by managing the logic that underpins the frontend. This includes processing user requests, performing calcuations, and returning the appropriate response.

## Key components of the backend

Each part serves a specific purpose in backend development, contributing to the overall functionality and performance of web applications. Here, we'll break down the essential elements, servers, databases and APIs and see how they work together to power smooth interactions. And also, Backend for Frontend (BFF).Backend for Frontend (BFF) is a design pattern where each frontend (website, mobile app, etc.) gets its own backend. Instead of every frontend talking directly to many backend services, the frontend only talks to its own BFF. The BFF collects the data it needs, combines it, and sends back a response that is optimized for that specific frontend. This makes the application faster, simpler to build, and easier to maintain. However, A BFF doesn't necessarily mean one server or one database. It means the different frontends share the same backend system (which could be one server or many microservices), while each frontend gets its own API. There are a few alternatives to BFF, wouldnt hurt to learn all these for the sake of experience n knowledge : 
1. Monolithic Backend
2. Shared Backend API
3. API Gateway (often used with BFF)
4. GraphQL

### Servers

Servers are crucial in the backend architecture. They manage requests from the client side, process them, and return the appropriate response. This could involve querying a database, executing server-side scripts or intergrating with third-party services.

Servers act as the bridge between the user and application's data, ensuring that requests are handled efficiently and securely.

### Databases

Databases store organize and manage data that is used by the application. They ensure data is easily accessible and can be manipulated as needed. You might have heard of some of the more popular databases such as:

+ MySQL : A widely used relational database management system known for its reliability and performance.
+ PostgreSQL : An advanced relational database with powerful features like support for complex queries.
+ MongoDB : A NoSQL document database known for its flexibility and rapid iteration possibilities.
+ Redis : An in-memory data structure store, used as a database, cache and message broker.

### APIs

API
