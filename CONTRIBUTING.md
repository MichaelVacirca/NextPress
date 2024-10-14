# Contributing to NextPress

First off, thank you for taking the time to contribute to **NextPress**! We value your input and are excited to work together to make this project a powerful, modern CMS framework.

## How to Contribute

### 1. Reporting Issues
If you find a bug or have an idea for a new feature, please [open an issue](https://github.com/michaelvacirca/nextpress/issues) on GitHub. Be as detailed as possible to help us understand the problem or feature request.

### 2. Fork the Repository
If you'd like to work on a new feature or bug fix:
1. **Fork** the repository to your GitHub account.
2. **Clone** the forked repository:
   ```bash
   git clone https://github.com/michaelvacirca/nextpress.git
   cd nextpress
   ```

### 3. Set Up Your Development Environment
- Make sure you have **Node.js** (v14 or higher) installed.
- Install dependencies for both **backend** (Strapi) and **frontend** (Next.js):
  ```bash
  # Backend setup
  cd backend
  npm install

  # Frontend setup
  cd ../frontend
  npm install
  ```
- You can now run both backend and frontend in development mode:
  ```bash
  # Run backend
  cd backend
  npm run develop

  # Run frontend
  cd ../frontend
  npm run dev
  ```

### 4. Creating a Branch
- Create a new branch for your feature or bug fix:
  ```bash
  git checkout -b feature/your-feature-name
  ```
- Follow the project's code style and conventions.

### 5. Making Changes
- Keep your changes focused and relevant to the specific issue you are solving.
- Write **clear commit messages** explaining the purpose of your changes.

### 6. Testing
- Make sure your changes don’t break existing features.
- Add new tests if your changes introduce new functionality.

### 7. Commit and Push
- Stage your changes:
  ```bash
  git add .
  ```
- Commit with a meaningful message:
  ```bash
  git commit -m "Add feature: description of the feature"
  ```
- Push to your branch:
  ```bash
  git push origin feature/your-feature-name
  ```

### 8. Open a Pull Request
- Navigate to the original repository on GitHub.
- Click the **New Pull Request** button.
- Make sure your branch passes all CI tests.
- Provide a **detailed description** of your changes, including the problem it solves.

### 9. Code Review
- Your pull request will be reviewed by the project maintainers.
- We might ask for some changes; please be receptive to feedback.

## Guidelines

### Coding Standards
- Follow the **JavaScript ES6** conventions.
- Use **Prettier** for code formatting and **ESLint** for linting.

### Commit Messages
- Use descriptive commit messages.
- Examples:
  - `Fix: Correct typo in README`
  - `Feat: Add user authentication to backend`

### Pull Request Etiquette
- Reference the issue your pull request is solving.
- Keep the pull request focused; avoid mixing unrelated changes.
- Ensure your pull request description provides context about what you changed and why.

## Community

- Join our [GitHub Discussions](https://github.com/michaelvacirca/nextpress/discussions) to share ideas, ask questions, or get help.
- Be respectful and inclusive to others—everyone’s contribution matters!

We look forward to seeing your contributions and working together to improve NextPress! 🚀
