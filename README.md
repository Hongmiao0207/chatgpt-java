# ChatGPT-Java

## Project Overview

This project is a Java implementation of ChatGPT, supporting the OpenAI official API. It is currently in development, with the goal to evolve into a comprehensive Java SDK for OpenAI. This SDK is intended to facilitate quick and easy integration of OpenAI's capabilities into Java projects.

In addition to API support, this project features a command-line mode for ChatGPT interactions. This allows users to engage in conversational dialogue directly through the command line, providing an easy and interactive way to explore ChatGPT's functionalities.

## Technical Architecture

The project is built on the Spring Boot framework, leveraging the power and simplicity it offers for developing stand-alone, production-grade applications.

Key aspects of the technical architecture include:

- **Reactive Programming**: Both the service and test stages of the project utilize reactive programming paradigms. This approach offers improved scalability and a more efficient way to handle asynchronous data streams.

- **Testing Framework**: The project uses JUnit 5 for testing. This modern testing framework for Java applications allows for more flexible and powerful testing scenarios.

- **Logging**: SLF4J (Simple Logging Facade for Java) is used for logging purposes. It serves as a simple facade or abstraction for various logging frameworks, allowing the end-user to plug in the desired logging framework at deployment time.

- **Utility Tools**: For ease of development, the project incorporates Hutool—a set of tools that include a rich set of features while remaining simple to use.

- **Token Calculation Algorithm**: The project employs the open-source token calculation algorithm from knuddelsgmbh/jtokkit. This algorithm is crucial for accurately calculating and handling token-based operations essential for interfacing with the OpenAI API.

## Future Goals

The vision for this project is to continuously extend its capabilities, eventually offering full support for all the features of the OpenAI API. The aim is to provide a robust, efficient, and easy-to-use Java SDK that can be seamlessly integrated into a wide range of Java applications, from small-scale projects to large enterprise systems.

Stay tuned for updates and enhancements as this project evolves.
