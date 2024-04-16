# Sunodo Cartesi Rollups Devcontainer Template

This repository provides a comprehensive VS Code devcontainer template specifically tailored for the [Sunodo Cartesi Rollups tool](https://sunodo.io/). It includes practical examples in both TypeScript and Python to help you get started with blockchain development using Cartesi Rollups.

### For an in-depth understanding of Cartesi Rollups, please consult the [Cartesi documentation](https://docs.cartesi.io/).

## Understanding Devcontainers

A Devcontainer, or Development Container, represents a fully containerized development environment, built using Docker. This setup serves to create a consistent, reproducible, and isolated development scenario that can be seamlessly shared and used across various machines and by different team members. By employing Devcontainers, developers can ensure that everyone involved in the project works in the exact same environment, avoiding the "it works on my machine" syndrome, and streamlining development processes.

## Prerequisites

Before you proceed with running the Devcontainer, ensure that the following tools are installed on your system:

> Note: This Devcontainer setup is compatible with [GitHub Codespaces](https://github.com/features/codespaces) and any other platforms that support Devcontainer environments.

- [Docker](https://www.docker.com/get-started): For creating and managing the development container.
- [Visual Studio Code](https://code.visualstudio.com/): As the integrated development environment (IDE).
- [Remote Development Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack): This extension pack includes a set of extensions that enable remote development in VS Code.

## Running the Devcontainer

To initiate and run the Devcontainer, follow these detailed steps:

1. **Clone the Repository:**
    Clone this repository to your local machine using the following command:
    ```shell
    git clone https://github.com/doiim/sunodo-devcontainer.git
    ```

2. **Open the Repository in VS Code:**
    Navigate to the cloned repository directory and open it in Visual Studio Code:
    ```shell
    cd sunodo-devcontainer
    code .
    ```

3. **Reopen in Devcontainer:**
    VS Code will automatically detect the presence of a Devcontainer configuration file. It will prompt you to 'Reopen in Container'. Select this option to shift your development environment into the defined container.

4. **Container Build and Initialization:**
    Allow some time for the Devcontainer to build and initialize. This process might take a few minutes, primarily depending on your internet connection speed.

5. **Start Developing:**
    Once the Devcontainer is active, you are all set to begin development using the Sunodo Cartesi Rollups template. The environment includes all necessary tools and dependencies pre-installed.

## Examples Included

To aid your development with Sunodo, this repository includes sample projects in TypeScript and Python. Here’s how you can use these examples:

- **TypeScript Example:**
    Located in the `typescript-example` directory, this sample provides a basic TypeScript DApp template. The primary application file is `src/index.ts`. To build and run this example, execute:
    ```shell
    cd typescript-example
    sunodo build  # Builds a Cartesi machine and prepares your DApp
    sunodo run    # Runs the application
    ```

- **Python Example:**
    Found in the `python-example` directory, this example includes a simple Python DApp template with `dapp.py` as the entry file. To build and run the Python example, follow these commands:
    ```shell
    cd python-example
    sunodo build  # Builds a Cartesi machine and prepares your DApp
    sunodo run    # Runs the application
    ```

By following the above guidelines, you can efficiently set up a development environment for Cartesi Rollups and start building decentralized applications using TypeScript or Python.