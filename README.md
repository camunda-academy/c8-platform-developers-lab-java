## Template for the Camunda 8 for Developers Training with Java

This is your starting point for the Camunda 8 for Developers training by using the Camunda Java client.
If you prefer using Spring refer to [this other repository](https://github.com/camunda-academy/c8-platform-developers-lab-spring)

## Prerequisites

- JDK 17 or higher
- A Java capable IDE such as IntelliJ IDEA or Eclipse (with Maven)

## Preparation steps

Verify that the project builds your local development environment by following these steps:

1. **Verify JDK Version**

   Make sure JDK 17 or higher is installed on your machine:
   `java -version`

2. **Clone and Import the Project**

   Clone the project repository and import it as a Maven project into your preferred Java-capable IDE.

3. **Configure Maven Settings (If Behind a Firewall)**

   If you're behind a corporate firewall, ensure that Maven is configured with the appropriate proxy settings in your `<user-home>/.m2/settings.xml`.

4. **Build and Test**

   Within the project directory, execute:
   `mvn clean install`

## Troubleshooting

If you encounter any issues:

- Confirm network settings and proxy configurations.
- Ensure all Maven dependencies are available and correctly downloaded.
- Review any error logs and resolve dependencies or configuration issues.
- For any unresolved issues, please contact the training coordinator with error details.
