Automation Framework Using Maven with CI/CD Integration

🚀 Technologies Used

Selenium WebDriver: For browser automation.
Maven: For dependency and build lifecycle management.
TestNG: Provides annotations, assertions, and parallel test execution.
Java: Core programming language for the framework.
IntelliJ IDEA: Integrated Development Environment (IDE) for writing and maintaining the codebase.
Docker: For creating lightweight containers and running tests in isolated environments.
GitHub Actions: For CI/CD pipeline integration and automated test execution.
📂 Structure Overview (Maven Project)

This framework follows the Page Object Model (POM) design pattern for better maintainability and scalability.

Folder Structure
src/main/java: Contains the reusable core components of the framework, including:
Base Classes: For WebDriver setup and teardown.
Page Objects: Encapsulates web page elements and interactions.
Utilities: Reusable methods for waits, screenshots, data reading, etc.
src/test/java: Contains the actual test cases implemented with TestNG.

📝 Key Features:-
1. Extent Reports
Generates visually rich HTML reports with timestamps.
Helps track test execution results and failures.
2. Logging
Logs are generated using Log4j2 for debugging and tracking.
Enables detailed insights into the framework's execution flow.
3. Docker Integration
Lightweight Containers: Docker enables running multiple containers simultaneously (10–15 containers at a time).
Cross-Platform Execution: Supports running tests across multiple operating systems on a single machine.
4. GitHub Integration
Version Control: Manages code changes efficiently with GitHub.
Collaboration: Facilitates collaboration, code reviews, and branching.
CI/CD Pipeline: Automated testing and deployment pipelines are configured using GitHub Actions.

🌟 Benefits of the Framework:
TestNG and Maven: A well-structured framework utilizing TestNG for efficient test execution and Maven for easy dependency management.
Page Object Model (POM): Improves readability, maintainability, and modularity of test cases.
Modular Design: Separates pages, utilities, and test cases into dedicated modules, enhancing scalability.
Reporting: Detailed, timestamped HTML reports provide insights into test execution results.
Reusable Components: Shared code in base classes and utility methods reduces redundancy and promotes reusability.
Industry Standard: Aligns with industry best practices for Selenium-based test automation.

Contact
For questions or suggestions, feel free to reach out:

Email: sanskriti2501@gmail.com
GitHub: https://github.com/SanskritiAYadav

