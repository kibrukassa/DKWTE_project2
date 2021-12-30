# Don't Know What To Eat

## Project Description

Don't Know What To Eat is a web application that randomly selects a restaurant based on the user address and the boundary specified. When the user types in the address and clicks on the 'Eat' button, the application will randomly select a restaurant for the user. Users can sign up and log in as a member to leave reviews about the restaurant by clicking the 'Let's Go' button after the application choose a restaurant. Admins have the authority to delete any relevant/inappropriate reviews.

## Technologies Used

-  Java 8
-  Hibernate
-  Spring Framework
-  PostgreSQL
-  Log4J,
-  Angular
-  TypeScript
-  HTML
-  CSS
-  Selenium
-  JUnit
-  Google Places API

## Features


* All users can get a randomly selected restaurant in their area and view all reviews on the restaurant.
* Users can sign up to become a member to write their comments/reviews about the restaurant.
* Admin can get a randomly generated restaurant, view reviews about the restaurant, and write reviews.
* Admin can search the reviews by restaurant name, review id, review title, and subject.
* Admin has the authority to delete inappropriate or irrelevant reviews.
* Both admins' and members' private information is securely stored in the database where the password is hash.


To-do list:
* Allow the user to be able to get a randomly generated restaurant by address.
* Utilize SonarCloud to detect bugs, vulnerabilities, code smells, and get a code coverage report.


## Getting Started

1. Be sure to have the Java 8 runtime environment installed.
2. Clone the repository:
https://github.com/kibrukassa/DKWTE_project2

3. Set the runtime environment:
  Application: in the src/main/resources package - Set up the runtime enviroment in the 'application.properties'
  Set up the database:
  Application: in the src/main/resources package
  Change the hibernate.ddl-auto in the 'application.properties' to create, validate, update
  SQL:
4. Create a schema name dwte

## Contributors

- Damilare Olaleye
- Danaya Chusuwan
- Ashli O'Neal
- Jahlil James
- Kibru Kassa

## License

This project uses the following license: [<license_name>](link).
