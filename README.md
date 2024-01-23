# Custom Home Organization Database System

**Overview**

Welcome to the Relational Database Project repository! This project focuses on revolutionizing data management for Custom Closet Contractors (C3), a fictional company specializing in custom home organization solutions.

The project addresses challenges posed by a paper-based system at C3, and proposes a comprehensive database solution by leveraging business analysis techniques, thereby optimizing processes from customer acquisition to installation. 

## Database Creation
- **Entities and Relationships**
  - Identified entities: Customer, Company, Consultation, Designer, Quote, Unit, Installation, Installer.
  - Defined relationships (e.g., Refers, Works_For, Gets) and cardinalities.
  - Created an Entity-Relationship Diagram and Relational Schema.
- **Functional Dependencies**
  - Established functional dependencies for key attributes.
  - Developed a detailed database diagram with populated tables.
  - Compiled a data dictionary for each relation.

## Data Population
- Utilized automatic data genertor tools for populating tables.

## Data Warehouse Implementation
- **Star Schema Design**
  - Designed a star schema for the data warehouse.
  - Identified dimensions (DimUnit, DimCustomer, DimInstallation) and the fact table (FactRevenue).
- **ETL Process**
  - Leveraged SQL code for populating data warehouse tables.
  - Showcased the first five rows of each populated data warehouse table.
- **Data Warehouse Tables**
  - Included tables such as DimUnit, DimCustomer, DimInstallation, and FactRevenue.
  - Highlighted data warehouse attributes and populated data.

## Ethical and Privacy Considerations
- Emphasized the importance of data privacy and security.
- Discussed potential ethical issues related to sensitive data like collecting multiple phone numbers, detailed addresses etc.

Thanks for visiting my project! Feel free to contribute.
