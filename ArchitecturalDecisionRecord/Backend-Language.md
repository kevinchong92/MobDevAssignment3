# Backend Language

**Status:** Proposed

**Deciders:** Kevin, Yuen Chong || Greg, Kuan-Ling Wu

**Date:** 2023-10-04

**Scenario 1**

Contents:

- [Context and Problem Statement](#context-and-problem-statement)
- [Decision Drivers](#decision-drivers)
- [Considered Options](#considered-options)
- [Decision Outcome](#decision-outcome)
- [Positive Consequences](#positive-consequences)
- [Negative Consequences](#negative-consequences)
- [Pros and Cons of the Options](#pros-and-cons-of-the-options)
- [Links](#links)

### Context and Problem Statement

We need to choose a backend programming language and framework to build the server-side components of the mobile app, including data synchronization, push notifications, payment processing, and analytics.

### Decision Drivers

- **Scalability:** The chosen language and framework should support scalability to handle potentially high traffic and data loads.

- **Ecosystem and Libraries:** Availability of libraries and tools for common tasks like push notifications, payment gateways, and analytics.

- **Performance:** The backend should be able to handle real-time data synchronization and provide low-latency responses.

### Considered Options

1. **Node.js with Express.js**

2. **Python with Django**

3. **Java with Spring Boot**

### Decision Outcome

**Chosen option:** "Node.js with Express.js" because it offers a combination of scalability, developer expertise, and a rich ecosystem of libraries and tools.

### Positive Consequences

- **Scalability:** Node.js is known for its ability to handle high concurrency, making it suitable for real-time features like push notifications and data synchronization.

- **Ecosystem and Libraries:** Node.js has a vast ecosystem of libraries and modules for various functionalities, including payment gateways, analytics, and push notifications.

- **Performance:** Node.js can provide low-latency responses, crucial for real-time features.

### Negative Consequences

- **Single-Threaded:** While Node.js is highly scalable due to its event-driven, non-blocking architecture, it may not be the best choice for CPU-intensive tasks.

### Pros and Cons of the Options

**Node.js with Express.js**

- Good, because it ensures scalability and real-time capabilities.

- Bad, because it may not be the best choice for CPU-bound tasks.

**Python with Django**

- Good, because Python is widely used and has a strong developer community.

- Bad, because it may not be as performant as Node.js for real-time features.

**Java with Spring Boot**

- Good, because it is known for its performance and scalability.

- Bad, because it may have a steeper learning curve for the team.

### Links

- [Node.js](https://nodejs.org/) - Official website for Node.js for reference and further information.
