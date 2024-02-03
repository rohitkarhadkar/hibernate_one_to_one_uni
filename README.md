# Hibernate Project with Advanced Mappings

This Hibernate project demonstrates advanced mappings, including a one-to-one unidirectional relationship between an `Instructor` entity and an `InstructorDetail` entity. In this mapping, an instructor is associated with an instructor detail, and when an instructor is deleted, the associated instructor detail is also deleted. This behavior is achieved using the `cascade=all` attribute.

## Features

- **Advanced Mappings**: Implements a one-to-one unidirectional mapping between `Instructor` and `InstructorDetail` entities, showcasing proficiency in advanced Hibernate concepts.
- **Cascade Operations**: Utilizes cascade operations to ensure that associated entities are also affected when performing CRUD operations on the parent entity.
- **Transaction Management**: Manages transactions using Hibernate's transaction API, ensuring data integrity and consistency.

## Project Structure

The project structure includes the following components:

- `Instructor` entity: Represents an instructor with basic details such as first name, last name, and email.
- `InstructorDetail` entity: Stores additional details for an instructor, such as YouTube channel and hobby.
- `Main` class: Contains the main method to demonstrate CRUD operations and advanced mappings.

## Usage

To run the Hibernate project locally, follow these steps:

1. Clone this repository.
2. Open the project in your preferred IDE.
3. Update the Hibernate configuration file (`hibernate.cfg.xml`) with your database connection details.
4. Run the `Main` class to execute the CRUD operations and observe the behavior of advanced mappings.

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or feature implementations, please open an issue or submit a pull request.

