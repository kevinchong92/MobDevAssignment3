# Data Storage

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

The mobile app needs to store various types of data, including product information, user profiles, order history, and loyalty program details. We must decide on the data storage solution that ensures data integrity, security, and optimal performance. The mobile app is developed using React Native.

### Decision Drivers

- **Data Integrity:** The selected data storage solution should prevent data corruption and ensure the accuracy of stored information.

- **Security:** Data, especially user-related data, should be protected from unauthorized access and breaches.

- **Performance:** Data retrieval and storage should be efficient to provide a responsive user experience.

- **Scalability:** The chosen solution should scale to accommodate the growing user base and data volume.

### Considered Options

1. **Relational Database Management System (RDBMS) like PostgreSQL or MySQL.**

2. **NoSQL Database like MongoDB or Firebase Firestore.**

3. **Hybrid Approach:** Use a combination of RDBMS and NoSQL databases for different types of data.

### Decision Outcome

**Chosen option:** Using a combination of PostgreSQL (RDBMS) like PostgreSQL or MySQL.

### Positive Consequences

- **Data Integrity:** RDBMS ensures data consistency and integrity, making it suitable for structured data like user profiles and orders.

- **Security:** PostgreSQL and MySQL come with built-in security features such as user authentication, role-based access control, and data encryption. This ensures that sensitive user data is protected from unauthorized access.

- **Performance:** RDBMS systems are optimized for complex queries and can handle large volumes of structured data efficiently. They also support indexing, which can significantly speed up data retrieval times.

- **Scalability:** RDBMS systems can be scaled vertically (by adding more resources to the existing server), and they can also be scaled horizontally (by adding more servers) using techniques like replication and sharding. This allows for flexibility in handling growing data and user loads.

### Negative Consequences

- **Complexity:** Setting up, configuring, and maintaining an RDBMS can be complex, especially for large-scale applications. This might require specialized knowledge and expertise.

- **Cost:** While there are open-source RDBMS options available, scaling them (especially in cloud environments) can lead to increased costs in terms of hardware, licensing, and maintenance.

### Pros and Cons of the Options

**Relational Database Management System (RDBMS)**

- Good, because it ensures data integrity and consistency.

- Good, because it provides strong security features.

- Bad, because it may not be as performant for unstructured data.

**NoSQL Database (MongoDB)**

- Good, because it excels at handling unstructured data.

- Good, because it provides scalability for high volumes of data.

- Bad, because it may not offer the same level of data integrity as RDBMS.

**Hybrid Approach**

- Good, because it leverages the strengths of both RDBMS and NoSQL databases.

- Bad, because it introduces complexity in managing two database systems.

### Links

- [PostgreSQL](https://www.postgresql.org/) - Official website for PostgreSQL, an open-source relational database management system.

- [MongoDB](https://www.mongodb.com/) - Official website for MongoDB, a NoSQL database known for its flexibility and scalability.
