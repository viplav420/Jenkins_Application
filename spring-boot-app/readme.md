# Spring-Boot-Java-Based-Application

**Spring Boot-based Java Web Application**

This project is a straightforward Spring Boot Java application built using Maven. Dependencies for Spring Boot are managed through the pom.xml file located in the root directory of the repository.

The application follows the MVC architecture, where the controller sends a page with title and message attributes to the view.

**Running the Application Locally**

Clone the repository and navigate to the directory:

Clone the repository from GitHub and navigate to the appropriate directory.

**Build the project using Maven:**

Use Maven to clean and package the project, generating the necessary artifacts in the target directory. These artifacts can be run locally or via Docker.

Note: To avoid potential issues with local setups, Java versions, and other dependencies, it’s recommended to use Docker.

**Run the application locally (requires Java 11):**

Execute the generated JAR file to run the application locally, which will be accessible at http://localhost:8080.

Using Docker:

Build a Docker image for the application and run it in a Docker container. The application will then be accessible at http://<ip-address>:8010.

**Next Steps**

Set up a local SonarQube server:

Install necessary packages and create a new user:

Install the unzip package and create a new user named sonarqube.

Download and extract SonarQube:

Download the SonarQube package from the official website and extract it.

Set permissions and start SonarQube:

Set the appropriate permissions for the SonarQube directory, change ownership to the sonarqube user, and start the SonarQube server.


