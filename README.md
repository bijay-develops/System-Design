# System-Design   by [The Webspace](https://github.com/The-WebSpace)

# Basics of System Design

### What is System Design?
- System design refers to the process of defining the architecture, components, modules, interfaces, and data of a system to satisfy specified requirements.

---

### Requirements Gathering Process
1. **Understand the Problem**: Identify the scope and objectives.
2. **Stakeholder Involvement**: Gather input from stakeholders.
3. **Document Requirements**: Clearly define functional and non-functional requirements.
4. **Prioritize Requirements**: Determine critical features for MVP.

---

### Functional vs Non-Functional Requirements
- **Functional Requirements**: Define specific behavior or functions (e.g., login, data retrieval).
- **Non-Functional Requirements**: Define system attributes like performance, scalability, and security.

---

### Components of System Design
- **Frontend**: User interfaces and experience.
- **Backend**: Servers, APIs, and databases.
- **Database**: Storage and retrieval of data.
- **Networking**: Communication between components.

---

### System Design Life Cycle | SDLC (Design)
1. Requirements Analysis
2. System Architecture
3. Component Design
4. Implementation
5. Testing
6. Deployment
7. Maintenance

---

# Scalability in System Design
- The ability of a system to handle growth in workload efficiently.

### Scalability and How to Achieve It
- **Horizontal Scaling**: Adding more machines.
- **Vertical Scaling**: Upgrading existing machines.

### Horizontal vs Vertical Scaling
| **Feature**            | **Horizontal Scaling** | **Vertical Scaling** |
|-------------------------|-------------------------|-----------------------|
| **Cost**               | Higher                 | Lower                |
| **Implementation**     | Complex                | Simpler              |
| **Scalability Limit**  | High                   | Limited              |

---

### Primary Bottlenecks that Hurt Scalability
- **Database Overload**
- **Network Latency**
- **CPU and Memory Constraints**

---

# System Architectural Styles

### Monolithic Architecture
- Single codebase.
- Pros: Simple to develop.
- Cons: Difficult to scale and maintain.

### Microservices Architecture
- Modular services.
- Pros: Scalable and maintainable.
- Cons: Complex to implement.

### Monolithic vs Microservices Architecture
| **Feature**    | **Monolithic** | **Microservices** |
|-----------------|----------------|-------------------|
| **Scalability**| Limited        | High             |
| **Flexibility**| Low            | High             |

### Event-Driven Architecture
- Systems respond to events asynchronously.

### Serverless Architecture
- Pay-as-you-go execution model.

---

# High-Level Design (HLD)

### What is High-Level Design?
- Focuses on the architecture and major components of a system.

---

## Availability in System Design
- Ensures the system is operational and accessible.

## Consistency in System Design
- Guarantees data integrity across the system.

## Reliability in System Design
- Ensures the system operates correctly and recovers from failures.

### CAP Theorem
- **Consistency**: Every read receives the latest write.
- **Availability**: Every request receives a response.
- **Partition Tolerance**: System functions despite network failures.

---

## Difference Between Concurrency and Parallelism
- **Concurrency**: Multiple tasks make progress simultaneously.
- **Parallelism**: Tasks execute simultaneously on different processors.

---

## Load Balancer
- Distributes traffic across servers to improve performance and reliability.

## Consistent Hashing
- Distributes data across nodes to ensure minimal redistribution during changes.

## Content Delivery Network (CDN)
- Caches content closer to users to reduce latency.

---

## Latency and Throughput
- **Latency**: Time taken to process a request.
- **Throughput**: Number of requests processed in a given time.

---

## Caching in System Design
- Improves performance by storing frequently accessed data.

## What is API Gateway?
- Manages APIs and facilitates communication between microservices.

## Message Queues
- Enables asynchronous communication between components.

## Communication Protocols
- HTTP, gRPC, WebSocket, etc.

## Network Protocols and Proxies
- TCP/IP, DNS, Reverse Proxy, etc.

---

## Unified Modeling Language (UML)
- Standard for visualizing system design.

---

# Databases in Designing Systems

### Which Database to Choose – SQL or NoSQL
- SQL: Structured data, complex queries.
- NoSQL: Flexible schema, high scalability.

### File and Database Storage Systems
- **File Storage**: Stores files in directories.
- **Database Storage**: Organized data in tables or collections.

### Database Replication in System Design
- Copies data across multiple servers for reliability.

### Database Sharding
- Splits data across multiple servers for scalability.

### Block, Object, and File Storage
- **Block**: High performance, low latency.
- **Object**: Scalability for unstructured data.
- **File**: Hierarchical structure.

### Normalization Process in DBMS
- Organizes data to reduce redundancy.

### Denormalization in Databases
- Optimizes read performance by adding redundancy.

---

# Low-Level Design (LLD)

### What is Low-Level Design or LLD?
- Focuses on implementation details.

### Object-Oriented Programming (OOP) Concepts
- Encapsulation, Inheritance, Polymorphism, Abstraction.

### Data Structures and Algorithms for System Design
- Hashmaps, Trees, Queues, Graphs, etc.

### Object-Oriented Analysis and Design
- Breaks down problems into objects and their interactions.

---

## Difference Between Authentication and Authorization
- **Authentication**: Verifies identity.
- **Authorization**: Grants permissions.

---

## Design Patterns
- Singleton, Factory, Observer, etc.

## Code Optimization Techniques
- Improve performance and readability.

## Unit Testing
- Tests individual components.

## Integration Testing
- Tests interactions between components.

---

## CI/CD: Continuous Integration and Continuous Delivery
- Automates testing and deployment processes.

## Introduction to Modularity and Interfaces
- Breaks systems into independent modules.

---

## Essential Security Measures in System Design
- Encryption, Firewalls, Authentication, etc.

---

# Interview Questions & Answers of System Design

### Popular Examples
- **URL Shortening Service**
- **Design Dropbox**
- **Design Twitter**
- **System Design Netflix**
- **Uber System Architecture**
- **Design BookMyShow**
- **Facebook Messenger**
- **WhatsApp Messenger**
- **Instagram**

---

## Tips for System Design Interviews

### How to Crack System Design Round
1. Understand the requirements.
2. Create a high-level design.
3. Address scalability and reliability.
4. Discuss trade-offs.

### 5 Tips to Crack Low-Level System Design Interviews
1. Understand OOP principles.
2. Focus on modularity.
3. Practice design patterns.
4. Write clean, optimized code.
5. Review example designs.

### Common System Design Concepts for Interview Preparation
1. Scalability.
2. Consistency.
3. High Availability.
4. Caching.
5. Load Balancing.

### Steps to Approach Object-Oriented Design Questions
1. Understand the problem.
2. Identify key objects.
3. Define relationships.
4. Use appropriate design patterns.
5. Create UML diagrams.

@The WebSpace
