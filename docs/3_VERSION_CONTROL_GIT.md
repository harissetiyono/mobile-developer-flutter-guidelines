# 3. Version Control (Git)

## Commit Message Guidelines

**Purpose:**

- Commit messages provide valuable context and history for changes made to the codebase. Clear and descriptive commit messages help developers understand the purpose and impact of each commit.

**Guidelines:**

These guidelines outline best practices for writing git commit messages. Consistent and informative commit messages help maintain a clean and understandable version history, making it easier to track changes and collaborate effectively.

### DO

- **Use Imperative Mood:** Write commit messages in the imperative mood.
- **Be Descriptive:** Provide a clear and concise description of the changes introduced by the commit.
- **Include Issue References:** If applicable, reference related issues, tasks, or feature requests in the commit message.

### DON'T

- **Avoid Vague Messages:** Refrain from using vague or ambiguous commit messages that do not provide meaningful context about the changes.
- **Don't Use Personal Pronouns:** Avoid using personal pronouns like "I" or "we" in commit messages.

### PREFER

- **Prefix Commit Messages:** Prefix commit messages with a relevant type identifier, such as "feat", "fix", "chore", etc., to categorize the type of change being made.
- **Use Conventional Commit Format:** Prefer using the conventional commit format, as defined by [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), to structure commit messages consistently across projects.

### AVOID

- **Avoid Excessive Detail:** Refrain from including excessive detail or technical jargon in commit messages, as it can clutter the version history.
- **Avoid Incomplete Messages:** Avoid committing incomplete or work-in-progress changes without providing context or explanation.

### CONSIDER

- **Consider Breaking Changes:** If a commit introduces breaking changes, consider explicitly mentioning them in the commit message to alert other developers.
- **Consider Scope:** When appropriate, include a scope identifier in the commit message to indicate the specific component or module affected by the changes.

### Examples for Each Commit Type

The commit message should be structured as follows:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

ref: <https://www.conventionalcommits.org/en/v1.0.0/#summary>

---
**feat (Feature)**: Introduces a new feature or functionality to the project.

- `feat: Add user authentication feature`
- `feat(auth): Add user authentication by google feature`

---
**fix (Bug Fix)**: Addresses and resolves an issue or bug within the project.

- `fix: Resolve issue with incorrect user permissions`
- `fix(permission): Resolve issue with incorrect user permissions`

---
**docs (Documentation)**: Updates or adds documentation, such as README files, comments, or inline documentation.

- `docs: Update README with installation instructions`
- `docs(readme): Update README with installation instructions`

---
**style (Code Style)** Implements changes related to code style, formatting, or whitespace.

- `style: Format code according to style guide`
- `style(format): Format code according to style guide`

---
**refactor (Code Refactor)**: Restructures existing code without changing its external behavior.

- `refactor: Simplify login component logic`
- `refactor(login): Simplify component logic`

---
**test (Tests)**: Adds, updates, or fixes tests related to the project's codebase.

- `test: Add unit tests for user registration`
- `test(registration): Add unit tests for user registration`

---
**chore (Chores)**: Implements miscellaneous tasks or changes that do not fit into any other category.

- `chore: Update dependencies to latest versions`
- `chore(deps): Update to latest versions`

---
**struct (Folder Structure)**: Adjusts or refactors the project's folder structure for better organization and readability.

- `struct: Reorganize project structure for improved readability`
- `struct(assets): Reorganize assets structure for improved readability`

---
**update (Updates)**: Updates dependencies, libraries, or other external resources used by the project.

- `update: Update library version to latest release`
- `update(library): Update version to latest release`

---
**enhance (Enhancements)**: Enhances or improves existing functionality or performance.

- `enhance: Improve performance of search algorithm`
- `enhance(search): Improve performance of search algorithm`

---
**revert (Reverts)**: Reverts a previous commit to undo changes that caused issues or unintended consequences.

- `revert: Revert previous commit that caused issue #123`
- `revert(issue123): Revert previous commit that caused issue #123`

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
