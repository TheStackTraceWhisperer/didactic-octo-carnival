# didactic-octo-carnival

A simple Hello World Java application with automated build and release workflows.

## Building the Project

```bash
mvn clean package
```

## Running the Application

```bash
java -jar target/hello-world-1.0.0.jar
```

## CI/CD Workflows

### Build Workflow
- Automatically runs on pushes and pull requests to the main branch
- Compiles the Java code and builds the JAR file
- Tests the JAR by running it

### Release Workflow
- Manually triggered via GitHub Actions
- Builds the JAR, packages it into a ZIP file
- Creates a public GitHub release with the artifact