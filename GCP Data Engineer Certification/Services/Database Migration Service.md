# Database Migration Service

- Overview: https://cloud.google.com/database-migration?hl=en
- Documentation: https://cloud.google.com/database-migration/docs/overview

Database Migration Service makes it easier for you to migrate your data to Google Cloud. Database Migration Service helps you lift and shift your MySQL and PostgreSQL workloads into Cloud SQL and AlloyDB for PostgreSQL, and lift and modernize your Oracle workloads into Cloud SQL for PostgreSQL.


## Use cases
The migration capabilities of Database Migration Service enable a variety of use cases:

### Lift and shift migration to a managed service
As part of an organization's move to Google Cloud, there's an opportunity to move from VM-based self-hosted databases to managed database cloud services. This allows teams to get out of the business of managing infrastructure, and enjoy the high availability, disaster recovery, and performance of running databases on managed services.

### Multi-cloud continuous replication
Much like the read replicas across regions, if data exists in another cloud provider, a migration job can be set up which continuously replicates the database into Google Cloud for multi-cloud read-availability. Database Migration Service doesn't support a dual-write scenario, that is writing to and reading from both the source and destination.