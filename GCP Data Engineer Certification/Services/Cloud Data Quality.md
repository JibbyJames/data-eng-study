# Cloud Data Quality

- Overview: https://github.com/GoogleCloudPlatform/cloud-data-quality

CloudDQ is a cloud-native, declarative, and scalable Data Quality validation Command-Line Interface (CLI) application for Google BigQuery. CloudDQ allows users to define and schedule custom Data Quality checks across their BigQuery tables. Data Quality validation results will be available in another BigQuery table of their choice. Users can then build dashboards or consume data quality outputs programmatically and monitor data quality from the dashboards and data pipelines.

CloudDQ takes as input Data Quality validation tests defined using declarative YAML configurations. Data Quality Rules can be defined using custom BigQuery SQL logic with parametrization to support complex business rules and reuse. For each Rule Binding definition in the YAML configs, CloudDQ creates a corresponding SQL view in BigQuery. CloudDQ then executes the view using BigQuery SQL Jobs and collects the data quality validation outputs into a summary table for reporting and visualization.