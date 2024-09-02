# Automated Refactoring Pipeline

## Tasks

- **Automated Design Smell Detection:** Develop a script or tool that
periodically scans the GitHub repository for design smells. This can include
metrics analysis, code pattern recognition, or any other relevant approach.
Utilize the capabilities of LLMs to assist in identifying potential design
issues in the codebase.

- **Automated Refactoring:** Implement an automated refactoring module that
takes the identified design smells and generates refactored code using LLMs.
Ensure that the refactoring process is robust, preserving the functionality of
the code while enhancing its design.

- **Pull Request Generation:** Design a mechanism to automatically create a
pull request with the refactored code changes.
Include detailed information in the pull request, such as the detected design
smells, the applied refactoring techniques, and any relevant metrics.

## High level overview of pipeline

- Developed a script to periodically scan the GitHub repository for design smells. Utilize the capabilities of Language Models (LLMs) to assist in identifying potential design issues in the codebase.
- Automated refactoring and pull request generation using GitHub workflows.

![Automated Refactoring Pipeline](../images/Automated-Refactoring.png)
