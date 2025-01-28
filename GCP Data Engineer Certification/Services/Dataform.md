# Dataform

## What is Dataform?

It's Google's answer to DBT.

Dataform is a collaborative data transformation platform designed to help teams manage data workflows and automate SQL-based data transformations in cloud data warehouses. It integrates with tools like BigQuery, Snowflake, and Redshift to simplify the process of building, testing, and deploying data pipelines.

## What can you do with Dataform?

- **Transform Data:** Use SQL-based transformations to clean, aggregate, and structure raw data for analytics.
- **Manage Dependencies:** Define relationships between datasets to ensure transformations occur in the correct order.
- **Version Control:** Leverage Git integration for version control and collaboration.
- **Test and Validate:** Automate the testing of transformations to ensure data accuracy and quality.
- **Orchestrate Workflows:** Schedule and monitor data workflows directly within the platform.
- **Collaborate:** Work as a team on shared data transformation projects in a streamlined environment.

## What sits under the hood?

Under the hood, Dataform operates as a layer that integrates with cloud data warehouses. It uses SQL-based configuration files to define transformations and dependencies, and it compiles these into queries executed directly in the data warehouse. It also supports JavaScript for dynamic SQL generation, making it flexible for complex transformations. Additionally, Dataform's orchestration engine schedules and monitors workflows, ensuring robust and reliable data pipelines.

## When is Dataform more suitable to use compared with other GCP services?

Dataform is more suitable to use compared with other GCP services like Cloud Dataflow or Dataprep when:

1. **You’re primarily working with SQL:** Dataform is optimized for SQL-based transformations and works well for teams familiar with SQL rather than programming-heavy solutions.
2. **You need collaborative workflows:** Its Git integration and collaboration features make it ideal for teams working on shared data transformation projects.
3. **You use BigQuery:** While it integrates with other warehouses, Dataform is particularly efficient for teams using BigQuery due to its deep integration.
4. **You want to simplify dependency management:** Dataform’s ability to define table dependencies and automatically sequence transformations simplifies complex workflows.
5. **You prefer a lightweight approach:** Unlike Cloud Dataflow, which requires coding in Python or Java, Dataform is lighter and faster to set up for SQL-focused workflows.
6. **You need testing and version control:** Dataform’s built-in testing framework and Git integration make it ideal for maintaining high-quality and versioned pipelines.
