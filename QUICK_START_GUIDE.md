# Quick Start Guide

Welcome to the Vivid Quick Start Guide! This guide will help you get up and running with Vivid quickly.

## Introduction

If you came here because you wanted to learn how to transform HR processes, manage talent effectively, or optimize total rewards with Vivid... you came to the right place! If not, stick around anyway. I promise it will be insightful.

### What's VIVID?

Vivid is an open-source platform offering a suite of intelligent tools designed to support HR professionals in HR transformation, talent management, and total rewards. It is free and open-source forever under your choice of the MIT or Apache 2.0 licenses.

Vivid has the following design goals:

- **Comprehensive**: Provide a complete toolset for HR transformation, talent management, and total rewards.
- **User-Friendly**: Accessible for HR professionals, yet flexible for advanced users.
- **Data-Driven**: Utilize data to offer insightful analytics and recommendations.
- **Modular**: Use only the components you need and customize them to suit your needs.
- **Efficient**: Optimize processes to save time and resources.
- **Collaborative**: Encourage community contributions and shared improvements.

Vivid is built in the open by volunteers using modern programming practices. The code is free and open-source because we believe that HR professionals should fully own their tools. HR is a critical function in organizations, and the development community can create better tools without the limitations of closed-source systems.

For a more in-depth introduction, check out the Introducing Vivid blog post.

### Stability Warning

Vivid is still in the early stages of development. Important features may be incomplete or evolving. Documentation is a work in progress. A new version of Vivid containing breaking changes to the API is released periodically. We provide migration guides, but we can't guarantee migrations will always be easy. Use only if you are willing to work in this environment.

If you are currently trying to pick a platform for your Next Big HR Project™, we recommend that you check out more established solutions. However, if you are excited about contributing to a growing project and shaping its future, Vivid is the perfect choice!

The Quick Start Guide is not a comprehensive guide to Vivid, and the next section Getting Started will help you with the setup of Vivid and learning the basics. For more exhaustive and complex resources, refer to the future Vivid Book and the Next Steps section.

Phew! If you haven't been scared away yet, let's move on to learning some Vivid!

## Getting Started

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (version 14.x or higher)
- [Docker](https://www.docker.com/) (optional, for running containers)

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/vivid.git
    cd vivid
    ```

2. **Install dependencies:**

    ```sh
    npm install
    ```

3. **Run the application:**

    ```sh
    npm start
    ```

    Your application should now be running at `http://localhost:3000`.

### Using Vivid

#### Setting Up

1. **Create a new project:**

    ```sh
    npm run create-project
    ```

2. **Configure your project:**

    Edit the configuration file located at `config/project-config.json` with your specific settings.

### Basic Commands

- **Start the development server:**

    ```sh
    npm start
    ```

- **Run tests:**

    ```sh
    npm test
    ```

- **Build for production:**

    ```sh
    npm run build
    ```

## Troubleshooting

If you encounter any issues, please refer to our [GitHub Discussions](https://github.com/yourusername/vivid/discussions) for support.

## Contributing

We welcome contributions! Please read our [Contributor's Guide](CONTRIBUTING.md) to get started.

---

Thank you for using Vivid! We hope this guide helps you get started. For more detailed information, check our [API Docs](API_DOCS.md).

## Next Steps

For more exhaustive and complex resources on Vivid, stay tuned for the Vivid Book. Meanwhile, explore the following resources:

- [Vivid API Docs](API_DOCS.md)
- [Community Discussions](https://github.com/yourusername/vivid/discussions)
- Future blog posts and tutorials

Happy transforming HR with Vivid!
