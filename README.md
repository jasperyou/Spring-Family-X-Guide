

## Spring Family X 指南

### ⚠️ 注意事项

* 本项目适合具有**Spring 使用经验**或**多年主流语言开发经验**的框架源码爱好者。
* 本项目基于 **Spring 5.16** 版本进行二次定制开发和学习。
* 环境配置请参考：[IntelliJ IDEA 导入 Spring 源码教程](http://www.glorze.com/1617.html)


### 拉取请求 (Pull Request) 规范

1.  **禁止修改 Spring 源码**。您可以在 Spring 允许的范围内进行扩展。
2.  允许对 Spring 源码添加**精简注释**。
3.  所有扩展代码或测试用例**必须**存放在 `test` 目录。
4.  在 `test` 目录下：
    * 如果存在**多个**类，请新建一个以 `X` 结尾的包（package）来存放。
    * 如果**只有单个**类，请将类名以 `X` 结尾。
5.  在提交 Pull Request 前，建议您先创建 [Issue](https://github.com/XiaoZiShan/Spring-Family-X-Guide/issues/new) 进行讨论。

---
