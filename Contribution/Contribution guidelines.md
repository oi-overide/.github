# Contribution Guidelines

Thank you for your interest in contributing to _Oi_! We welcome contributions that improve and expand the CLI code generation tool. Please take a moment to read through these guidelines to ensure a smooth collaboration.

## Getting Started

1. **Fork the Repository:** Start by forking the repository on GitHub.
2. **Clone Your Fork:** Clone your forked repository to your local machine.

``` bash	
git clone https://github.com/your-username/oi.git
```

3. **Create a New Branch:** Create a new branch from `dev` and use a descriptive branch name that reflects the purpose of the change. 

```bash
git switch dev
git checkout -b feature-or-bugfix-name
```

4. **Install Dependencies:** If you haven't already, install `pnpm` globally, as _Oi_ uses `pnpm` for dependency management.

```bash
pnpm install
```

## Code Standards

- **TypeScript:** Ensure all code is written in TypeScript, following the existing structure and practices.
- **Linting and Formatting:** Run `eslint` to keep code clean and consistent. Use Prettier for formatting.

```bash
pnpm lint
```
## Making Changes

1. **Be Clear and Concise:** Write clear, concise code with descriptive comments when needed.
2. **Test Your Changes:** Verify that your updates work correctly. If applicable, add or modify tests to ensure reliability.
3. **Documentation:** Update or add relevant documentation to help future contributors and users understand your changes.

## Pull Request Process

1. **Commit Changes:** Make meaningful, atomic commits. Include descriptive messages for each change.

```bash
git commit -m "Fix: Resolved X bug in Y module"
```
 
2. **Push to Your Branch:**

```bash
git push origin feature-or-bugfix-name`
```

3. **Open a Pull Request:** Go to the GitHub repository and open a pull request from your branch. Follow the template provided, explaining the purpose and context of your changes.
4. **Target Branch**: For any pull request `dev` should be the base branch. 

## Code Review and Feedback

- A project maintainer will review your pull request. Please be open to constructive feedback and make adjustments as requested.
- Once approved, a maintainer will merge your changes into the _main_ branch.

## Additional Guidelines

- **File Structure:** Place new files and features in appropriate directories according to the existing structure.
- **Commit Style:** Use conventional commit messages (e.g., `Fix`, `Feat`, `Docs`) to maintain a consistent history.
- **Testing:** Run all tests before submitting, and ensure no existing functionality is broken.

## Thank You!

We appreciate your contributions and effort to improve _Oi_. Your work helps make this tool better for everyone. Thank you for being a part of the community!