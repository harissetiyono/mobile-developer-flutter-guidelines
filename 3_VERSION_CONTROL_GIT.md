# 3. Version Control (Git)

## Commit Message Guidelines

**Purpose:**

- Commit messages provide valuable context and history for changes made to the codebase. Clear and descriptive commit messages help developers understand the purpose and impact of each commit.

**Guidelines:**

- Follow the conventional commit format (e.g., [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)) to structure commit messages.
- Start the commit message with a concise, imperative verb in the present tense (e.g., "Add", "Fix", "Update").
- Provide a brief summary of the changes in the commit subject line (50 characters or less).
- Optionally, include a more detailed description of the changes in the commit body, wrapped at 72 characters per line.
- Reference any relevant issue or task numbers in the commit message (e.g., "Fix #123").

## Branching Strategy

**Purpose:**

- A branching strategy defines how code changes are managed and integrated into the codebase. It helps maintain a clean history, enable parallel development, and facilitate collaboration among team members.

**Guidelines:**

- Adopt a branching model that aligns with the project's requirements and team's workflow (e.g., GitFlow, GitHub Flow).
- Use feature branches for developing new features or enhancements, bugfix branches for addressing defects, and release branches for preparing stable releases.
- Ensure that each branch serves a clear purpose and follows naming conventions (e.g., feature/, bugfix/`name`, release/`version`).

## Pull Request Guidelines

**Purpose:**

- Pull requests (PRs) facilitate code review, feedback, and collaboration among team members. Following consistent PR guidelines ensures that changes are reviewed thoroughly and integrated seamlessly into the codebase.

**Guidelines:**

- Provide a descriptive title for the pull request that summarizes the changes introduced.
- Include a detailed description of the changes, rationale, and any relevant context in the PR description.
- Assign reviewers to the PR based on their expertise and involvement in the affected code.
- Address any review comments and ensure that the PR meets the project's coding standards, test coverage requirements, and acceptance criteria before merging.

## Git Workflow Overview

The team follows a Git workflow based on feature branching and pull requests to manage code changes efficiently. The typical workflow consists of the following steps:

1. **Create Feature Branch:**
Create a new feature branch from the `develop` branch to work on a specific feature or task.

2. **Implement Changes:**
Implement the desired changes in the feature branch, following coding standards and best practices.

3. **Submit Pull Request:**
Once the changes are complete, submit a pull request to merge the feature branch into the `develop` branch.

4. **Code Review:**
Reviewers conduct a thorough code review of the pull request, providing feedback and suggestions for improvement.

5. **Address Feedback:**
Address any feedback or comments raised during the code review process, making necessary revisions to the code.

6. **Merge Pull Request:**
After receiving approval from reviewers and resolving any discussions, merge the pull request into the `develop` branch.

7. **Release to Production:**
Periodically, create release branches from the `develop` branch to prepare release candidates for production deployment.

By following these version control guidelines and workflow practices, the team can collaborate effectively, maintain code quality, and ensure smooth integration of changes into the codebase.

<p align="center">will be updated regularly 🔥</p>
