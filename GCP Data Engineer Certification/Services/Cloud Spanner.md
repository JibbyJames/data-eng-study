# Cloud Spanner

- Overview: https://cloud.google.com/spanner?hl=en
- Intro video: https://www.youtube.com/watch?v=BtaUNTrtEKk

Google Cloud Spanner is a fully managed, scalable, relational database service offered by GCP. It combines the benefits of relational database systems with the horizontal scalability and high availability typically associated with non-relational databases. Cloud Spanner is designed to provide global consistency, high availability, and strong transactional support, making it suitable for a variety of demanding applications.

## Best for
- Global applications requiring low-latency, highly available access to relational data.
- Mission-critical applications needing strong transactional consistency.
- Large-scale online transaction processing (OLTP) systems.

## Difference
- Combines the scalability of NoSQL databases with the strong consistency and transactional support of relational databases.
- Offers global distribution and horizontal scalability, which traditional relational databases often cannot provide.

## Use Cases
- Global Applications: Applications that require a globally distributed database with low-latency access and strong consistency across regions. For example, a global e-commerce platform or a multinational financial service.
- Mission-Critical Applications: Applications that demand high availability and strong transactional consistency, such as banking systems, financial trading platforms, or healthcare record systems.
- Large-Scale OLTP Systems: Online transaction processing (OLTP) systems that require the ability to scale horizontally while maintaining ACID properties, such as inventory management systems, reservation systems, or gaming backends.
- Real-Time Analytics: Applications that need to process and analyze data in real time while maintaining consistency and accuracy, such as fraud detection systems or real-time bidding platforms.