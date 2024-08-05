# My TypeScript Node.js Starter

When I start a new project, I notice that I end up writing the same configurations every time. So, I decided to move them to a separate repository. Now, when I start a new project, I simply clone this repository and enjoy the development process without spending time on setup.

If you like my basic configuration setup, feel free to use it in your own projects!

## Features

- **TypeScript Configuration**: Includes TypeScript settings for a smooth development experience.
- **Prettier**: Code formatting setup to keep your code clean and consistent.
- **ESLint**: Linting configuration to enforce coding standards and catch potential issues.
- **Commitlint**: Ensures that your commit messages follow the conventional commit format.
- **Husky**: Manages Git hooks for pre-commit and other Git-related tasks.
- **Release-It**: Automates versioning and release process.

## Getting Started

Before starting work on the project, please take a moment to review its structure. You can customize it to fit your needs. For example, if you have a different directory structure, you can adjust the paths for source files by replacing `lib` with `src` or any other directory you use.

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/DIY0R/my-ts-node-starter.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd my-ts-node-starter
   ```

3. **Install Dependencies**:

   ```bash
   npm install
   ```

4. **Start Developing**:

   You can now start developing your project !

## Scripts

Here are some useful scripts available in this project:

- **Build**:

  ```bash
  npm run build
  ```

  Compiles the TypeScript code using `tsc`.

- **Prettier**:

  ```bash
  npm run prettier
  ```

  Checks code formatting using Prettier.

- **Prettier: Fix**:

  ```bash
  npm run prettier:fix
  ```

  Automatically fixes code formatting issues using Prettier.

- **Lint**:

  ```bash
  npm run lint
  ```

  Lints code using ESLint.

- **Lint: Fix**:

  ```bash
  npm run lint:fix
  ```

  Automatically fixes linting issues using ESLint.

- **Prepare**:

  ```bash
  npm run prepare
  ```

  Installs Git hooks using Husky.

- **Release**:

  ```bash
  npm run release
  ```

  Automates the versioning and release process using Release-It.

## Contributions

Feel free to submit issues and pull requests if you find any bugs or have suggestions for improvements.

---

Happy coding!
