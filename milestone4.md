---
layout: page
title: Milestone 4
parent: Projects
nav_order: 4
---
### Milestone 4 : Development and Deployment

Milestone 4 focuses on developing, testing, and deploying a user-facing application that integrates all components from previous milestones. This milestone ensures the project is functional, well-tested, and ready for real-world usage through automation and deployment strategies.

### Key dates:

- Due date: Nov 19th


### Template Repository
[Template Repository](https://github.com/)


### Objectives:
- **App Design, Setup, and Code Organization:**
  - Design the application’s overall architecture, including the user interface and underlying code structure.
  - Emphasize clean code organization for maintainability and efficiency.
- **APIs & Frontend Integration:**
  - Develop robust APIs for communication between the front end and back end.
  - Implement a user-friendly front-end interface using these APIs for a seamless user experience.
- **Continuous Integration (CI):**
  - Implement CI using GitHub Actions or a similar tool.
  - Automate building, testing, and deployment processes to ensure new code merges are automatically validated.
- **Automated Testing:**
  - Write and integrate unit tests and end-to-end tests for APIs and the front end.
  - Ensure all tests run automatically in the CI pipeline, with results reported on every commit or pull request.

### Deliverables:
1. **Application Design Document:**
   - A detailed document outlining the application’s architecture, user interface, and code organization.
   - **Should Include:**
     - **Solution Architecture:** High-level overview of system components and their interactions.
     - **Technical Architecture:** Specific technologies, frameworks, and design patterns used.
2. **APIs & Frontend Implementation:**
   - Working code for APIs and the front-end interface.
   - **Should Include:**
     - **GitHub Repository:** All source code with logical organization and proper documentation.
     - **README File:** Description of application components, setup instructions, and usage guidelines.
3. **Continuous Integration Setup:**
   - A functioning CI pipeline that runs on every push or merge.
   - **Pipeline Must Include:**
     - **Code Build and Linting:** Automated build process and code quality checks using linting tools (e.g., ESLint, Flake8).
     - **Automated Testing:** Execution of unit and end-to-end tests with test results reported.
     - **Deployment Steps:** (If deployment is required) Automated deployment to a specified environment.
4. **Automated Testing Implementation:**
   - Integration of automated tests within the CI pipeline.
   - **Should Include:**
     - **Unit Tests:** For individual components and functions.
     - **End-to-End Tests:** Covering user flows and interactions.
     - **Test Coverage Reports:** Integrated into the CI pipeline to monitor code coverage.
5. **Test Documentation:**
   - Detailed explanations of the testing strategy and implemented tests.
   - **Should Include:**
     - **Testing Tools Used:** (e.g. PyTest)
     - **Instructions to Run Tests Manually:** For developers to replicate test results locally.