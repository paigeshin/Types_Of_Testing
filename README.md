# Types_Of_Testing

[https://hackr.io/blog/types-of-software-testing](https://hackr.io/blog/types-of-software-testing)

[https://www.slideshare.net/Bugraptors/performance-testing-1](https://www.slideshare.net/Bugraptors/performance-testing-1)

# Unit Testing

- Independent
- Automatic
- Repeatable
- Readable

### What should you test?

**DOs**

- **Do** test Application domain
- **Do** test application user interface by automating unit tests

**DON’Ts**

- **Don’t** test generated code
- **Don’t** test issues caught by compiler
- **Don’t** test dependency or third party code

### Unit Testing ⇒ Domain Testing

- Performed in **Memory**
- Don’t access network
- Don’t hit the database
- Don’t use the file system

### Bank App Anecdote

- Transfer Funds
    - Should have a source account and destination account
    - Source account should have the funds
    - Should deduct amount from source after successful transfer
    - Should credit amount to destination after successful transfer
    - Should charge transfer fee

---

# Integration Testing

- Software has many different components

### Software Components Examples

- UI
- Domain
- Services
- Database

### Integration Testing

- Components are combined and tested together to evaluate interactions between them
- Integration tests goes through real world scenarios of how the whole system will work
- The final step is acceptance testing. The client tests the software on actual hardware using actual data

---

# Acceptance Testing

- Acceptance Testing is a level of testing where the system is tested for **acceptability**
- Acceptance testing is testing performed to satisfy the business criteria
- Acceptance testing is performed on business requirements and needs
- Acceptance testing is performed by client or the end user

---

# Performance Testing

- Performance Testing is the process of determining the **speed and effectiveness** of software

### Standards

- Throughput
- Response time
- Tuning
- Benchmarking

### Throughput

- The number of requests/transactions processed by the application in a specified time duration

### Response Time

- Response time is defined as the delay between the point of request and the first response

### Tuning

- Tuning is an iterative process that we use to identify and eliminate bottlenecks in the applications

### Benchmarking

- Benchmarking is the practice of comparing business processes and performance metrics to industry bests and best practices from other companies
