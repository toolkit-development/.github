# Toolkit GitHub Repositories

Welcome to the **Toolkit** GitHub organization! This organization hosts multiple repositories, each serving a specific purpose within the toolkit ecosystem. Below is an overview of each repository and its role in building a comprehensive toolkit for managing canisters, projects, and SNS-based governance.

For a more in depth look we would recommend looking into the [toolkit documentation](https://docs.ic-toolkit.app)

## Repository Overview

### 1. `toolkit_docs`
- **Language**: TypeScript
- **Description**: The repository for the Toolkit documentation, built with Docusaurus. It provides guides, reference materials, and explanations for setting up and managing toolkit projects, integrating canisters, and using the toolkit's features.

### 2. `toolkit_frontend`
- **Language**: Svelte
- **Description**: The frontend application for the Toolkit, providing users with an intuitive interface to manage their toolkit projects, canisters, and SNSes. This UI simplifies project interactions, making it easy for users to deploy and monitor canisters.

### 3. `toolkit_registry`
- **Language**: Rust
- **Description**: Acts as the registry for all toolkit and SNS projects the user follows, and keeps track of privately owned canisters

### 4. `project_root_registry`
- **Language**: Rust
- **Description**: Serves as the controller for all custom root canisters within the toolkit. This registry keeps track of custom roots and can initiate upgrades when required.

### 5. `project_root`
- **Language**: Rust
- **Description**: Manages the core operations of toolkit projects. This canister serves as the main controller for all the canisters under a toolkit project, handling configuration, deployment, and governance settings.

### 6. `ic-toolkit-utils`
- **Language**: Rust
- **Description**: A utility library for the Toolkit, containing reusable components, helper functions, and structures that streamline the development of toolkit canisters and services.

### 7. `proposal_validator`
- **Language**: Rust
- **Description**: A public repository for validating SNS proposals for executing generic nervous system functions.

---

These repositories collectively support the **Toolkit**, offering a complete solution for developers and users to manage projects, canisters, and governance with flexibility and ease. Each repository contributes to a modular architecture, allowing for future expansions and integrations. 

Feel free to explore each repository and contribute to the toolkit’s evolution!
