# NoSQL Data Management and Visualization Project

## Project Overview

This project demonstrates the integration and management of customer data using various NoSQL database technologies. The primary objective was to design an efficient data structure and visualize the relationships between different entities, leveraging the strengths of multiple NoSQL systems such as Redis, MongoDB, and Neo4j.

## Key Tasks

### 1. ERD Design from Customer Data
The project began with the design of an Entity-Relationship Diagram (ERD) based on the data provided in `CustDetails.txt` and `LatePmts.txt`. The ERD visually represents the entities involved and their relationships. For fields in the data that lacked clear definitions, logical interpretations were made, and meaningful labels were assigned to ensure clarity in the diagram.

### 2. Data Storage in Redis
The records from the customer data files were stored in Redis using a key-value format. Redis was chosen for its efficiency in handling this type of structured data, allowing quick access and manipulation of records.

### 3. JSON Document Creation and MongoDB Storage
The first two records from the dataset were converted into JSON format and stored in MongoDB. This step demonstrated the use of MongoDB’s document-based storage, which is well-suited for handling semi-structured data like JSON.

### 4. XML Conversion and MongoDB Storage
After storing the records in JSON format, the corresponding MongoDB collection was deleted. The same data was then converted into XML format and stored again in MongoDB. This task highlighted MongoDB's flexibility in handling various data formats, ensuring that data can be managed and queried efficiently in both JSON and XML formats.

### 5. Graph-Based Diagram Design
A graph-based diagram was designed to visualize the entities and relationships derived from the customer data. In this diagram, nodes represent the entities (e.g., customers, payments), while edges represent the relationships between these entities (e.g., payment history, customer details).

### 6. Implementation in Neo4j
The graph-based design was implemented in Neo4j using `CREATE` statements to establish nodes and relationships. Neo4j's graph database structure was utilized to efficiently manage and query the interconnected data, providing insights into the relationships between different entities.

## Technologies Used

- **Redis**: For storing and managing data in a key-value format.
- **MongoDB**: For storing and managing data in both JSON and XML formats.
- **Neo4j**: For implementing and querying the graph-based data model.
- **ERD Tools**: Used to design the Entity-Relationship Diagram for the database structure.

## Conclusion

This project successfully integrates multiple NoSQL technologies to manage and visualize customer data. By designing an ERD, storing data in Redis and MongoDB, and visualizing relationships in Neo4j, the project showcases the flexibility and efficiency of NoSQL databases in handling complex, multi-format data structures. The work demonstrates a comprehensive approach to modern data management and visualization using diverse NoSQL systems.


![image](https://github.com/user-attachments/assets/49111f3d-dd7a-4cdd-accd-ede4c03f4e7c)
