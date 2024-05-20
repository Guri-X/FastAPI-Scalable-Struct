# FastAPI Scalable Structure

## Folders

- **Services**: Components that either perform prolonged operations or have direct interactions with end users are categorized as services. For example, a Django application, react application, etc.

- **Infrastructure**: All configuration files related to the chosen tools are kept here. These configuration files are typically extensive and are available in formats such as *YAML*, *JSON*, or *HCL*.

- **Tools**: To minimize redundancy in your tasks, it’s beneficial to store your tools in a central location. This area also act as a repository for any scripts that do not yet have a specific designated space.

- **Lib**: Intended for internal library packages that are to be uploaded to private registries such as PyPI.

- **CI/CD**: Contains *YAML* configuration file for the Continuous Integration/Continuous Deployment (CI/CD) pipeline. It will also contain DockerFiles require for the CI/CD.

## To-Do API Folder

### Requirements

- **Pytest**: A tool utilized for writing and executing automated tests.
- **Pytest-Cov**: Generate reports on code coverage.
- **Black**: Responsible for taking care of code formatting.
- **Isort**: For optimizing imports.
- **Flake8**: Used to check complaince with PEP8 (a coding standard).
- **Bandit**: For checking security vulnerabilities in the code.
- **Safety**: Used to check for any vulnerabilities in the packages.

## Backend API Tests

### Folders

- **Unit**: This will house the unit tests.
- **Integration**: This will contain the integration tests.
- **E2E**: This will house the *end-to-end* tests.

### Test notations

- **GIVEN**: Describes the initial conditions or context.
- **WHEN**: Explains what is happening and needs to be tested.
- **THEN**: Outlines the expected outcome.