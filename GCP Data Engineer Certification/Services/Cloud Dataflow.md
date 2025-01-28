# Cloud Dataflow

It is an Apache Beam powered solution.

- Overview: https://cloud.google.com/dataflow?hl=en
- What is DataFlow video: https://www.youtube.com/watch?v=KalJ0VuEM7s
- Demo video: https://www.youtube.com/watch?v=dXhF3JJg3mE
- Dataflow in a minute: https://www.youtube.com/watch?v=XdsuDOQ9nkU


### **Use Cloud Dataflow When:**
1. **Complex Data Processing Pipelines**  
   Dataflow is a fully managed service for **processing large-scale datasets** using both batch and streaming pipelines.  
   - **Example**: Transform and enrich large IoT data streams and write the results to BigQuery.

2. **Distributed Processing**  
   If your workload involves handling **large datasets** that require distributed computation across multiple nodes for parallelism and scalability.  
   - **Example**: Aggregating millions of events per second from IoT sensors.

3. **Stateful Stream Processing**  
   Dataflow is built for handling **stateful processing** over time, such as windowed aggregations, joins, or detecting patterns in real-time streams.  
   - **Example**: Real-time fraud detection with event correlation over sliding windows.

4. **Batch + Streaming in One Tool**  
   If you need a unified tool that can handle **both batch and real-time (streaming) processing** pipelines.  
   - **Example**: Load historical batch data into BigQuery while simultaneously processing new data streams.

5. **Scalability and Performance**  
   For workloads that involve **high-volume data ingestion**, such as terabytes of logs or continuous streams of telemetry data, Dataflow automatically scales to handle the load.  
   - **Example**: Processing log files from multiple sources and aggregating metrics.


### Comparison to Cloud Functions

| **Feature**                  | **Cloud Functions**                                 | **Cloud Dataflow**                                      |
|------------------------------|----------------------------------------------------|-------------------------------------------------------|
| **Type of Workload**          | Lightweight, event-driven tasks                   | Large-scale, distributed data processing              |
| **Triggers**                  | Event-based (HTTP, Pub/Sub, Cloud Storage, etc.)  | Batch and real-time streaming pipelines               |
| **Data Volume**               | Small to moderate                                 | Large-scale (terabytes or more)                      |
| **Execution Model**           | Stateless, single-purpose functions               | Stateful, complex pipelines with parallel execution   |
| **Scalability**               | Auto-scales but for short-lived tasks             | Auto-scales for massive workloads                    |
| **Cost Efficiency**           | Best for low-frequency or short-lived tasks       | Best for continuous, large-scale processing           |
| **Use Case Example**          | Send a Slack alert when a Pub/Sub message arrives | Stream IoT data, enrich it, and write it to BigQuery  |
