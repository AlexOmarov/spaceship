# Documentation Guide

[← Back to Project Root](../README.md)

This directory serves as the central hub for all Spaceship project documentation.
Below is a guide to the folder structure and the logical organization of the documentation.

## 🚀 New to the project?

If you are just starting, we recommend reading these dependencies in order:

1. **[Project Overview](./project/README.md)** - Understand what we are building.
2. **[Development Workflow](./development/README.md)** - Set up your environment and learn how to contribute.

## 📂 Documentation Structure

The documentation is organized into specific subdirectories to separate concerns:

### 1. 📁 [project](./project/README.md)
>
> **General project information and business context.**

* **[Project Description](./project/README.md)**: Extensive details about what the project is and its goals.
* **[Business Context](./project/README.md)**: Links to upper-level business requirements, vision, and strategy.
* **[Basic Info](./project/README.md)**: Ownership, current status, and high-level administrative details.

### 2. 📁 [architecture](./architecture/README.md)
>
> **Technical design and structural documentation.**

* **[Overview](./architecture/README.md)**: Brief description of the system architecture.
* **Diagrams**:
  * **Class Diagrams**: Structure of the code and data models (Mermaid compatible).
  * **Use Case Diagrams**: User interactions and functional requirements.
  * **Sequence Diagrams**: Runtime process flows and component interactions.

### 3. 📁 [development](./development/README.md)
>
> **Guidelines and rules for contributors.**

* **[Workflow](./development/README.md)**: How to work with the program day-to-day.
* **[Code Style](./development/README.md)**: Principles, formatting rules, and naming conventions.
* **[Core Libraries](./development/README.md)**: specific list of allowed/used libraries and their versions.
* **[Testing Guide](./development/README.md)**: Instructions on how to write tests (TDD, Unit, Integration, E2E).

### 4. 📁 [quality](./quality/README.md)
>
> **Quality assurance standards and processes.**

* **[QA Strategies](./quality/README.md)**: Methodologies used to ensure software quality.
* **[Tools](./quality/README.md)**: Description of analysis tools, linters, and checkers used.

### 5. 📁 [operations](./operations/README.md)
>
> **DevOps, deployment, and infrastructure.**

* **[Deployment](./operations/README.md)**: Instructions for deploying the application to various environments.
* **[CI/CD](./operations/README.md)**: Extensive description of the Continuous Integration and Delivery pipelines.

### 6. 📁 [reference](./reference/README.md)
>
> **Technical specifications and glossary.**

* **[API Specifications](./reference/README.md)**: Detailed API contracts and interface docs.
* **[Glossary](./reference/README.md)**: Dictionary of domain terms and common vocabulary.

### 7. 📁 [security](./security/README.md)
>
> **Security policies and procedures.**

* **[Policy](./security/README.md)**: Vulnerability reporting and security standards.

---

## ✍️ Documentation Maintenance

To keep documentation healthy:

1. **Diagrams**: Use [Mermaid.js](https://mermaid.js.org/) for diagrams whenever possible to allow version control and easy editing.
    * Place diagrams in the relevant `architecture/` section.
2. **Syncing**: Update documentation in the same Pull Request as the code changes.
    * See `CONTRIBUTING.md` for specific requirements.
3. **Format**: Use standard Markdown.
