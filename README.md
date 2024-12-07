# HIBERNATE_INHERITENCE

Hibernate Inheritance Mapping: Table Per Concrete Class with Unions
This project demonstrates how to implement inheritance mapping in Hibernate using the Table Per Concrete Class with Unions strategy. The application models a base entity and two specific sub-entities, each stored in its own database table.

Key Features
Inheritance Mapping Strategy:

The project follows the Table Per Concrete Class approach.
Each subclass has its own table, including all properties from the base class.
Technology Stack:

Java: For developing the application logic.
Hibernate: For object-relational mapping and database persistence.
MySQL: As the relational database for data storage.
Maven: For managing dependencies and project build.
Database Integration:

Records for different entity types are stored in separate tables, with properties from the base class included in all tables.
The base class defines shared attributes, while subclasses add unique attributes.
