# Conventional Commit Cheat Sheet

A simple guide to help you understand and apply the [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/) standard for versioning in your projects.

---

## 🚀 Basic Structure

Each commit message follows this structure:

- **type**: Describes the change (e.g., `feat`, `fix`, `chore`)
- **scope**: Optional. Refers to the area of the project being affected (e.g., `api`, `frontend`)
- **description**: A short description of the change.

---

## 📋 Types of Commit

### 1. **feat**: A new feature for the user or system

Example:  
`feat(auth): add Google login feature`  
Explanation: This commit introduces a new feature for user authentication, allowing Google login.

---

### 2. **fix**: A bug fix for the user or system

Example:  
`fix(button): resolve issue with button hover state`  
Explanation: This commit fixes a bug where the button hover state was not functioning properly.

---

### 3. **chore**: Routine tasks like maintenance or updating dependencies

Example:  
`chore(deps): update react to version 17.0.2`  
Explanation: This commit updates the dependencies, specifically React, to a newer version.

---

### 4. **docs**: Documentation updates

Example:  
`docs(readme): update installation instructions`  
Explanation: This commit updates the README file with clearer installation instructions.

---

### 5. **style**: Changes related to code style (e.g., formatting, missing semi-colons)

Example:  
`style(button): fix button alignment in CSS`  
Explanation: This commit makes code style adjustments, like fixing the alignment of a button in CSS.

---

### 6. **refactor**: Code change that neither fixes a bug nor adds a feature

Example:  
`refactor(auth): simplify login form validation logic`  
Explanation: This commit refactors the login form validation code to make it simpler without adding any new functionality.

---

### 7. **test**: Adding or updating tests

Example:  
`test(auth): add unit tests for login function`  
Explanation: This commit adds new unit tests to test the login function in the authentication module.

---

### 8. **build**: Changes that affect the build system or external dependencies

Example:  
`build(webpack): add webpack config for production build`  
Explanation: This commit modifies the build system (Webpack) configuration to improve the production build.

---

### 9. **ci**: Continuous integration-related changes

Example:  
`ci(gitlab): update CI config for deployment pipeline`  
Explanation: This commit updates the GitLab CI configuration to improve the deployment pipeline.

---

## 🧑‍💻 Learn More

For a deeper understanding of Conventional Commits, check out the official documentation: [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).

---

## 💡 Tips

- Keep your messages clear and concise.
- Use the type that best represents the change you made.