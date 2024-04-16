# Sunodo Cartesi Rollups Devcontainer Template

This repository provides a VS Code devcontainer template for [Sunodo Cartesi Rollups tool](https://sunodo.io/), along with examples in TypeScript and Python.

### For detailed information on how Cartesi Rollups work, please refer to the [Cartesi documentation](https://docs.cartesi.io/).

## What is a Devcontainer?

A devcontainer is a development environment containerized using Docker. It allows developers to define a consistent and reproducible development environment that can be easily shared across different machines and team members. Devcontainers provide a complete and isolated development environment, including all the necessary tools, dependencies, and configurations.

## Prerequisites

Before running the devcontainer, make sure you have the following prerequisites installed on your machine:

> Note: This devcontainer can also be used with [GitHub Codespaces](https://github.com/features/codespaces) or platforms that support devcontainers.

- [Docker](https://www.docker.com/get-started)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Remote Development Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)


## Running the Devcontainer

To run the devcontainer, follow these steps:

1. Clone this repository to your local machine:

    ```shell
    git clone https://github.com/doiim/sunodo-devcontainer.git
    ```

2. Open the cloned repository in Visual Studio Code:

    ```shell
    cd sunodo-devcontainer
    code .
    ```

3. Visual Studio Code will detect the devcontainer configuration and prompt you to reopen the project in a devcontainer. Click on "Reopen in Container" to start the devcontainer.

4. Wait for the devcontainer to build and start. This may take a few minutes depending on your internet connection.

5. Once the devcontainer is up and running, you can start working with the  Sunodo template. The devcontainer provides all the necessary tools and dependencies for developing and testing your DApps.

## Examples

This repository includes examples in TypeScript and Python to help you get started with Sunodo. You can find the examples in the following directories:

- `typescript-example`: Contains a sample TypeScript DApp template. The entrypoint for the application is the `src/index.ts` file. To build and run the TypeScript example, follow these steps:
    1. Build step: the sunodo build command builds a Cartesi machine and compiles your application so that it is ready to receive requests and inputs.
        ```shell
        cd typescript-example
        sunodo build
        ```
    3. Run the application:
        ```shell
        sunodo run
        ```

- `python-example`: Contains a sample Python DApp template. The entrypoint for the application is the `dapp.py` file. To build and run the Python example, follow these steps:
    1. Build step: the sunodo build command builds a Cartesi machine and compiles your application so that it is ready to receive requests and inputs.
        ```shell
        cd python-example
        sunodo build
        ```
    3. Run the application:
        ```shell
        sunodo run
        ```

Feel free to explore these examples and modify them according to your needs.