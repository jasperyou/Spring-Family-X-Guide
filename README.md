<div align="center"><a name="readme-top"></a>

<img height="120" src="https://github.com/jasperyou/spring-guide-x/blob/master/Spring_Framework_Logo_2018.svg.png">
</div>

# Spring Guide X 指南

本项目旨在通过**添加精简注释**和**提供单元测试**来帮助开发者更深入地理解 **Spring 5 框架**的核心原理与设计思想。我们致力于创建一个高质量的学习资源，让Spring源码的学习过程变得更加友好和高效。

**简体中文** · [English](./README.en-US.md)  · [变更日志](./CHANGELOG.md) · [开启新话题][https://github.com/jasperyou/spring-guide-x/issues/new]


## ⚠️ 注意事项

* 本项目适合具有**Spring 使用经验**或**多年主流语言开发经验**的框架源码爱好者。
* 本项目基于 **Spring 5.16** 版本进行二次定制开发和学习，请确保您的本地环境与此版本兼容。
* 环境配置请参考：[IntelliJ IDEA 导入 Spring 源码教程](http://www.glorze.com/1617.html)。

---

## 🎯 项目目标

* 为 Spring 5.16 核心模块的关键代码提供**精炼、准确的中文注释**。
* 补充**清晰、有效的单元测试**，演示Spring特性的用法或验证特定功能。
* 搭建一个**开放协作的平台**，鼓励社区成员共同学习和贡献。

---

## 🚀 如何贡献 (Pull Request 规范)

我们非常欢迎社区的贡献！为了确保项目的质量和一致性，请遵循以下贡献规范：

### 1. 代码修改限制

* **禁止修改 Spring 原始源码**。我们只允许在 Spring 框架允许的范围内进行扩展（例如：实现接口、继承抽象类、使用Spring提供的扩展点等）。请保持Spring源码的纯净性，以确保学习基准的一致。

### 2. 注释规范

* 允许对 Spring 源码添加**精简注释**。注释应专注于解释：
    * **核心设计意图**：为何这样设计？
    * **复杂逻辑**：难以一眼看懂的代码块。
    * **关键概念**：重要变量、参数或方法的职责。
    * **易混淆点**：容易产生误解的代码行为。
* 请**避免过度解释**显而易见的简单代码。
* 建议使用 **Javadoc 格式**的注释，以提高可读性和后续文档生成的可能性。

### 3. 代码存放位置

* 所有您的**扩展代码或测试用例**都**必须**存放在项目的 `test` 目录中。这有助于将您的贡献与原始的 Spring 源码清晰地区分开。

### 4. 命名约定

为了明确区分贡献代码，请遵循以下命名约定：

* 在 `test` 目录下：
    * 如果存在**多个**相关的类（例如：演示同一个Spring模块的多个测试），请新建一个以 `X` 结尾的包（package）来存放。
        * **示例**：`com.example.spring.family.x.guide.tx.MyTransactionXService`
    * 如果**只有单个**类（例如：一个独立的单元测试类），请将类名以 `X` 结尾。
        * **示例**：`com.example.spring.family.x.guide.aop.MyAopProxyXTest`

### 5. 提交前沟通

* 在提交 Pull Request (PR) 前，**强烈建议您先创建 [Issue](https://github.com/jasperyou/spring-guide-x/issues/new)** 进行讨论。这有助于我们：
    * 避免重复工作。
    * 确保您的贡献方向与项目目标一致。
    * 在编码前获得反馈，从而提高 PR 的质量和被接受的几率。
    * 更好地进行协作和分工。

---

## 🤝 贡献流程概览

1.  **Fork** 本仓库到您的 GitHub 账户。
2.  将 Fork 后的仓库 **Clone** 到本地。
3.  根据 [IntelliJ IDEA 导入 Spring 源码教程](http://www.glorze.com/1617.html) 配置您的开发环境。
4.  根据您打算贡献的内容，**创建 Issue** 进行讨论。
5.  在本地修改代码（添加注释或编写测试用例），并遵循上述规范。
6.  提交您的修改到您的 Fork 仓库。
7.  创建 **Pull Request** 到本仓库的 `master` 分支。
8.  等待项目维护者的评审和反馈。

---

感谢您对 Spring Guide X 指南的关注与支持！让我们一起构建一个更好的Spring框架学习项目！

---

