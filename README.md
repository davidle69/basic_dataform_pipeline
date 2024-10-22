# Basic Dataform Pipeline
## Background
This project serves as a practical learning environment for understanding and implementing Dataform workflows within Google Cloud Platform (GCP). It was created to provide hands-on experience with Dataform's data transformation capabilities and to serve as a reference implementation for future client engagements requiring data transformation solutions.

## Objective
The primary objective of this project is twofold:
1) To demonstrate a working Dataform workflow that performs basic data transformations
2) To serve as a template that can be adapted and expanded for future client engagements requiring similar data transformation capabilities

## Scope and Considerations
The project assumes the existence of raw, untransformed data in a BigQuery table. The scope includes basic transformation operations such as data type casting from STRING to other appropriate formats. While intentionally kept simple, the workflow demonstrates core Dataform functionalities and best practices.

## Technical Implementation
The solution requires specific GCP permissions to function correctly. The service account must be granted the following roles:
- Service Account Token Creator
- Secret Manager Secret Accessor
- BigQuery Data Editor
- BigQuery Data Viewer
- BigQuery Job User

## Workflow Overview
1) Source Data: The workflow begins with raw data stored in a BigQuery table
2) Transformation: Basic transformations are applied to selected columns
3) Output: Transformed data is written to a new table within the same BigQuery dataset
   
This implementation provides a foundation for understanding Dataform's capabilities and can be expanded to accommodate more complex transformation requirements.
