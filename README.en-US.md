<div align="center"><a name="readme-top"></a>

<img height="120" src="https://github.com/jasperyou/spring-guide-x/blob/master/Spring_Framework_Logo_2018.svg.png">
</div>

# Spring Guide X

This project aims to help developers gain a deeper understanding of the **Spring 5 framework's** core principles and design by **adding concise comments** and **providing unit tests**. We are committed to creating a high-quality learning resource that makes the process of studying Spring source code more accessible and efficient.

**English** · [简体中文](./README.md) · [Changelog](./CHANGELOG.md) · [Open an Issue](https://github.com/jasperyou/spring-guide-x/issues/new)

-----

## ⚠️ Important Notes

  * This project is suitable for framework source code enthusiasts with **prior Spring experience** or **several years of mainstream language development experience**.
  * This project is based on **Spring 5.16** for secondary customization and learning. Please ensure your local environment is compatible with this version.
  * For environment setup, please refer to: [IntelliJ IDEA Importing Spring Source Code Tutorial](http://www.glorze.com/1617.html).

-----

## 🎯 Project Goals

  * Provide **concise, accurate English comments** for the key code within Spring 5.16's core modules.
  * Supplement with **clear, effective unit tests** to demonstrate Spring features or validate specific functionalities.
  * Establish an **open collaboration platform** to encourage community members to learn and contribute together.

-----

## 🚀 How to Contribute (Pull Request Guidelines)

We warmly welcome community contributions\! To ensure the quality and consistency of the project, please adhere to the following contribution guidelines:

### 1\. Code Modification Restrictions

  * **Do not modify the original Spring source code**. We only permit extensions within the scope allowed by the Spring framework (e.g., implementing interfaces, extending abstract classes, using Spring-provided extension points). Please keep the Spring source code pristine to maintain a consistent learning baseline.

### 2\. Commenting Guidelines

  * You are permitted to add **concise comments** to the Spring source code. Comments should focus on explaining:
      * **Core Design Intent**: Why was this designed this way?
      * **Complex Logic**: Code blocks that are not immediately intuitive.
      * **Key Concepts**: The responsibilities of important variables, parameters, or methods.
      * **Potential Confusions**: Code behaviors that are easily misunderstood.
  * Please **avoid over-explaining** self-evident, simple code.
  * We recommend using **Javadoc format** for comments to enhance readability and potential future documentation generation.

### 3\. Code Location

  * All your **extension code or test cases must** be placed in the project's `test` directory. This helps to clearly distinguish your contributions from the original Spring source code.

### 4\. Naming Conventions

To clearly identify contributed code, please follow these naming conventions:

  * Within the `test` directory:
      * If there are **multiple** related classes (e.g., demonstrating several tests for the same Spring module), please create a new package ending with `X` to contain them.
          * **Example**: `com.example.spring.family.x.guide.tx.MyTransactionXService`
      * If there is **only a single** class (e.g., an independent unit test class), please append `X` to the class name.
          * **Example**: `com.example.spring.family.x.guide.aop.MyAopProxyXTest`

### 5\. Pre-submission Communication

  * Before submitting a Pull Request (PR), we **strongly recommend that you first create an [Issue](https://github.com/jasperyou/spring-guide-x/issues/new)** for discussion. This helps us to:
      * Avoid duplicate efforts.
      * Ensure your contribution aligns with the project's goals.
      * Receive feedback before coding, thus improving the quality and acceptance rate of your PR.
      * Facilitate better collaboration and task allocation.

-----

## 🤝 Contribution Workflow Overview

1.  **Fork** this repository to your GitHub account.
2.  **Clone** your forked repository to your local machine.
3.  Configure your development environment according to the [IntelliJ IDEA Importing Spring Source Code Tutorial](http://www.glorze.com/1617.html).
4.  Based on your intended contribution, **create an Issue** for discussion.
5.  Modify the code locally (add comments or write test cases), following the guidelines above.
6.  Commit your changes to your forked repository.
7.  Create a **Pull Request** to the `master` branch of this repository.
8.  Await review and feedback from the project maintainers.

-----

Thank you for your interest and support in Spring Guide X\! Let's build a better Spring framework learning project together\!

-----
