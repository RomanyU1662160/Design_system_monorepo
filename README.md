# DESIGN_SYSTEM_MONOREPO

 The monorepo is managed by Lerna and NX! This repository houses multiple packages and applications under one roof, allowing for easier management, code sharing, and streamlined development processes.

## Structure

This monorepo is organized into two main folders:

- **packages**: This directory contains all the reusable packages/modules that are shared across all applications.
- **apps**: Here, you'll find the various applications built on top of the shared packages. Additionally, the React playground resides within this directory.

## Tools Used

### Lerna

[Lerna](https://github.com/lerna/lerna) is a tool for managing JavaScript projects with multiple packages. It optimizes the workflow around managing multi-package repositories with git and npm.

### NX

[NX](https://nx.dev/) is a set of extensible dev tools for monorepos, enabling efficient development, scaling, and automation. It provides capabilities such as code generation, testing, and more, tailored specifically for monorepo setups.

## Design System

The design system is implemented using Sass, following the principles of Atomic design. This approach enables the creation of consistent, modular, and scalable UI components across our applications.

## Getting Started

To get started with development, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-monorepo.git
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Start developing!

## Contributing

If you'd like to contribute, please follow these guidelines:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

Please ensure that your pull request adheres to our coding standards and includes tests and documentation where necessary.

## Support

If you encounter any issues or have any questions, feel free to [open an issue](https://github.com/your-username/your-monorepo/issues) on GitHub.

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for using our monorepo! Happy coding! 🚀
