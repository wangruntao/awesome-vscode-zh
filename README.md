# 🎯 VSCode 好用插件收藏

这个仓库旨在整理和收集好用的 VSCode 插件，帮助开发者快速找到适合自己开发需求的扩展工具。

## 📚 目录

- [官方 VSCode 扩展](#官方-vscode-扩展)

  - [代码编辑](#代码编辑)
  - [语法高亮](#语法高亮)
  - [代码格式化](#代码格式化)
  - [代码折叠](#代码折叠)
  - [自动补全](#自动补全)
  - [调试器](#调试器)
  - [Git 和版本控制](#git-和版本控制)
  - [多语言支持](#多语言支持)
- [编程语言相关扩展](#编程语言相关扩展)

  - [常见编程语言](#常见编程语言)
    - [Python](#python)
    - [JavaScript/TypeScript](#javascripttypescript)
    - [C/C++](#cc)
    - [Java](#java)
    - [Go](#go)
    - [PHP](#php)
    - [Rust](#rust)
    - [Ruby](#ruby)
    - [Swift](#swift)
    - [Kotlin](#kotlin)
  - [前端开发](#前端开发)
    - [HTML/CSS/JS](#htmlcssjs)
    - [React/Angular/Vue](#reactangularvue)
  - [后端开发](#后端开发)
    - [Node.js](#nodejs)
    - [.NET/C#](#netc)
    - [Java (Spring等)](#java-spring等)
    - [Ruby on Rails](#ruby-on-rails)
  - [数据库](#数据库)
    - [SQL](#sql)
    - [NoSQL](#nosql)
    - [GraphQL](#graphql)
- [工具类扩展](#工具类扩展)

  - [版本控制与协作](#版本控制与协作)
  - [项目管理](#项目管理)
  - [容器与虚拟化](#容器与虚拟化)
  - [调试与性能分析](#调试与性能分析)
- [界面和美化类扩展](#界面和美化类扩展)

  - [主题与图标](#主题与图标)
  - [代码高亮与标记](#代码高亮与标记)
  - [字体与样式](#字体与样式)
- [生产力提升扩展](#生产力提升扩展)

  - [Snippet 扩展](#snippet-扩展)
  - [代码生成和快捷操作](#代码生成和快捷操作)
  - [文档与注释工具](#文档与注释工具)
- [自动化与部署类扩展](#自动化与部署类扩展)

  - [构建工具](#构建工具)
  - [部署与 CI/CD](#部署与-cicd)
  - [持续集成](#持续集成)
- [数据与分析类扩展](#数据与分析类扩展)

  - [数据分析](#数据分析)
  - [数据库管理与分析](#数据库管理与分析)
- [Web 和前端开发类扩展](#web-和前端开发类扩展)

  - [前端框架与库](#前端框架与库)
  - [Web 开发工具](#web-开发工具)
- [跨平台与远程开发类扩展](#跨平台与远程开发类扩展)

  - [远程开发工具](#远程开发工具)
  - [虚拟化与容器](#虚拟化与容器)
- [AI 和机器学习扩展](#ai-和机器学习扩展)

  - [机器学习](#机器学习)
  - [人工智能辅助开发](#人工智能辅助开发)

## 🎈 项目背景

在日常开发中，VSCode 已经成为了很多开发者的首选编辑器。但市面上的插件琳琅满目，有些插件针对中文用户的友好度还不够，本项目便是为了整理出那些真正适合中文开发环境的插件，方便大家在众多扩展中进行筛选和使用。

虽然已经有同类的项目[awesome-vscode](https://github.com/viatsko/awesome-vscode)整理了大量的插件，但是对于英语基础不好的用户，还是需要花费一定的时间去筛选。

## 官方 VSCode 扩展

### 代码编辑

| 插件名称                                                                                                             | 描述                  | 下载量                                                                                                | 评分                                                                                               | 预览                        |
| -------------------------------------------------------------------------------------------------------------------- | --------------------- | ----------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | --------------------------- |
| [Chinese (Simplified)](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-zh-hans)      | VSCode 的中文语言包   | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/MS-CEINTL.vscode-language-pack-zh-hans) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/MS-CEINTL.vscode-language-pack-zh-hans) | [预览](assets/chinese.png)     |
| [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode) | AI 辅助的代码补全工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/VisualStudioExptTeam.vscodeintellicode) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/VisualStudioExptTeam.vscodeintellicode) | [预览](assets/intellicode.gif) |

### 语法高亮

| 插件名称                                                                                                          | 描述                    | 下载量                                                                                                  | 评分                                                                                                 | 预览                        |
| ----------------------------------------------------------------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | --------------------------- |
| [Jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest)                                         | JavaScript 测试框架集成 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Orta.vscode-jest)                         | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Orta.vscode-jest)                         | [预览](assets/jest.gif)        |
| [Python Test Explorer](https://marketplace.visualstudio.com/items?itemName=LittleFoxTeam.vscode-python-test-adapter) | Python 测试框架集成     | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/LittleFoxTeam.vscode-python-test-adapter) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/LittleFoxTeam.vscode-python-test-adapter) | [预览](assets/python-test.gif) |

### 代码格式化

| 插件名称                                                                                        | 描述                     | 下载量                                                                                      | 评分                                                                                     | 预览                           |
| ----------------------------------------------------------------------------------------------- | ------------------------ | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------ |
| [Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client) | 轻量级的 REST API 客户端 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/rangav.vscode-thunder-client) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/rangav.vscode-thunder-client) | [预览](assets/thunder-client.gif) |
| [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)               | 发送 HTTP 请求和查看响应 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/humao.rest-client)            | ![Rating](https://img.shields.io/visual-studio-marketplace/r/humao.rest-client)            | [预览](assets/rest-client.gif)    |

### 代码折叠

| 插件名称                                                                                             | 描述                 | 下载量                                                                                              | 评分                                                                                             | 预览                        |
| ---------------------------------------------------------------------------------------------------- | -------------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | --------------------------- |
| [AWS Toolkit](https://marketplace.visualstudio.com/items?itemName=AmazonWebServices.aws-toolkit-vscode) | AWS 服务集成工具     | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/AmazonWebServices.aws-toolkit-vscode) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/AmazonWebServices.aws-toolkit-vscode) | [预览](assets/aws-toolkit.gif) |
| [Azure Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-node-azure-pack)     | Azure 服务开发工具包 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-vscode.vscode-node-azure-pack)     | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-vscode.vscode-node-azure-pack)     | [预览](assets/azure-tools.gif) |

### 自动补全

| 插件名称                                                                                                   | 描述             | 下载量                                                                                                  | 评分                                                                                                 | 预览                        |
| ---------------------------------------------------------------------------------------------------------- | ---------------- | ------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | --------------------------- |
| [Snyk Security](https://marketplace.visualstudio.com/items?itemName=snyk-security.snyk-vulnerability-scanner) | 代码安全漏洞扫描 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/snyk-security.snyk-vulnerability-scanner) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/snyk-security.snyk-vulnerability-scanner) | [预览](assets/snyk.gif)        |
| [GitGuardian](https://marketplace.visualstudio.com/items?itemName=GitGuardian.gitguardian-vscode)             | 敏感信息泄露检测 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/GitGuardian.gitguardian-vscode)           | ![Rating](https://img.shields.io/visual-studio-marketplace/r/GitGuardian.gitguardian-vscode)           | [预览](assets/gitguardian.gif) |

### 调试器

| 插件名称                                                                                                   | 描述                    | 下载量                                                                                            | 评分                                                                                           | 预览                             |
| ---------------------------------------------------------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | -------------------------------- |
| [Performance Profiler](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-js-profile-flame) | JavaScript 性能分析工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-vscode.vscode-js-profile-flame)  | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-vscode.vscode-js-profile-flame)  | [预览](assets/profiler.gif)         |
| [Memory Inspector](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-js-profile-memory)    | 内存使用分析工具        | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-vscode.vscode-js-profile-memory) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-vscode.vscode-js-profile-memory) | [预览](assets/memory-inspector.gif) |

### Git 和版本控制

| 插件名称                                                                         | 下载量                                                                            | 评分                                                                           | 预览                      |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ------------------------- |
| [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)      | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/eamodio.gitlens)    | ![Rating](https://img.shields.io/visual-studio-marketplace/r/eamodio.gitlens)    | [预览](assets/gitlens.gif)   |
| [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/mhutchie.git-graph) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/mhutchie.git-graph) | [预览](assets/git-graph.gif) |

### 多语言支持

| 插件名称                                                                                | 描述               | 下载量                                                                                 | 评分                                                                                | 预览                        |
| --------------------------------------------------------------------------------------- | ------------------ | -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | --------------------------- |
| [i18n Ally](https://marketplace.visualstudio.com/items?itemName=Lokalise.i18n-ally)        | 国际化翻译管理工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Lokalise.i18n-ally)      | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Lokalise.i18n-ally)      | [预览](assets/i18n-ally.gif)   |
| [Translation](https://marketplace.visualstudio.com/items?itemName=hancel.google-translate) | 集成的翻译工具     | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/hancel.google-translate) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/hancel.google-translate) | [预览](assets/translation.gif) |

## 编程语言相关扩展

### 常见编程语言

#### Python

| 插件名称                                                                             | 下载量                                                                                  | 评分                                                                                 | 预览                    |
| ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | ----------------------- |
| [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)          | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-python.python)         | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-python.python)         | [预览](assets/python.gif)  |
| [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-python.vscode-pylance) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-python.vscode-pylance) | [预览](assets/pylance.gif) |
| [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)       | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-toolsai.jupyter)       | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-toolsai.jupyter)       | [预览](assets/jupyter.gif) |

#### JavaScript/TypeScript

| 插件名称                                                                                                                   | 下载量                                                                                         | 评分                                                                                        | 预览                           |
| -------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------ |
| [ES7+ React/Redux/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/dsznajder.es7-react-js-snippets) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/dsznajder.es7-react-js-snippets) | [预览](assets/react-snippets.gif) |
| [Vue Language Features](https://marketplace.visualstudio.com/items?itemName=Vue.volar)                                        | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Vue.volar)                       | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Vue.volar)                       | [预览](assets/vue.gif)            |
| [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)                           | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Angular.ng-template)             | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Angular.ng-template)             | [预览](assets/angular.gif)        |

#### C/C++

| 插件名称                                                                                       | 下载量                                                                                | 评分                                                                               | 预览                     |
| ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ------------------------ |
| [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools)                     | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/mtxr.sqltools)          | ![Rating](https://img.shields.io/visual-studio-marketplace/r/mtxr.sqltools)          | [预览](assets/sqltools.gif) |
| [MongoDB for VS Code](https://marketplace.visualstudio.com/items?itemName=mongodb.mongodb-vscode) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/mongodb.mongodb-vscode) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/mongodb.mongodb-vscode) | [预览](assets/mongodb.gif)  |

#### Java

| 插件名称                                                                                                    | 下载量                                                                                      | 评分                                                                                     | 预览                        |
| ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | --------------------------- |
| [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)        | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/vscjava.vscode-java-pack)     | ![Rating](https://img.shields.io/visual-studio-marketplace/r/vscjava.vscode-java-pack)     | [预览](assets/java-pack.gif)   |
| [Spring Boot Extension Pack](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-boot-dev-pack) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Pivotal.vscode-boot-dev-pack) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Pivotal.vscode-boot-dev-pack) | [预览](assets/spring-boot.gif) |

#### Go

| 插件名称                                                         | 下载量                                                                   | 评分                                                                  | 预览               |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------------------- | ------------------ |
| [Go](https://marketplace.visualstudio.com/items?itemName=golang.Go) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/golang.Go) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/golang.Go) | [预览](assets/go.gif) |

#### PHP

| 插件名称                                                                                          | 下载量                                                                                      | 评分                                                                                     | 预览                         |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------- |
| [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/bmewburn.vscode-intelephense) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/bmewburn.vscode-intelephense) | [预览](assets/intelephense.gif) |

#### Rust

| 插件名称                                                                                | 下载量                                                                               | 评分                                                                              | 预览                          |
| --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- | ----------------------------- |
| [Rust Analyzer](https://marketplace.visualstudio.com/items?itemName=matklad.rust-analyzer) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/matklad.rust-analyzer) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/matklad.rust-analyzer) | [预览](assets/rust-analyzer.gif) |

#### Ruby

| 插件名称                                                               | 下载量                                                                       | 评分                                                                      | 预览                 |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------- | -------------------- |
| [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/rebornix.Ruby) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/rebornix.Ruby) | [预览](assets/ruby.gif) |

#### Swift

| 插件名称                                                                              | 下载量                                                                         | 评分                                                                        | 预览                  |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | --------------------------------------------------------------------------- | --------------------- |
| [Swift for VS Code](https://marketplace.visualstudio.com/items?itemName=sswg.swift-lang) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/sswg.swift-lang) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/sswg.swift-lang) | [预览](assets/swift.gif) |

#### Kotlin

| 插件名称                                                               | 下载量                                                                     | 评分                                                                    | 预览                   |
| ---------------------------------------------------------------------- | -------------------------------------------------------------------------- | ----------------------------------------------------------------------- | ---------------------- |
| [Kotlin](https://marketplace.visualstudio.com/items?itemName=fwcd.kotlin) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/fwcd.kotlin) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/fwcd.kotlin) | [预览](assets/kotlin.gif) |

### 前端开发

#### HTML/CSS/JS

| 插件名称                                                                                                                   | 下载量                                                                                         | 评分                                                                                        | 预览                           |
| -------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------ |
| [ES7+ React/Redux/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/dsznajder.es7-react-js-snippets) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/dsznajder.es7-react-js-snippets) | [预览](assets/react-snippets.gif) |
| [Vue Language Features](https://marketplace.visualstudio.com/items?itemName=Vue.volar)                                        | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Vue.volar)                       | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Vue.volar)                       | [预览](assets/vue.gif)            |
| [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)                           | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Angular.ng-template)             | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Angular.ng-template)             | [预览](assets/angular.gif)        |

#### React/Angular/Vue

| 插件名称                                                                                                       | 描述                     | 下载量                                                                                                     | 评分                                                                                                    | 预览                             |
| -------------------------------------------------------------------------------------------------------------- | ------------------------ | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | -------------------------------- |
| [Spring Boot Dashboard](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-boot-dashboard) | Spring Boot 服务管理面板 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/vscjava.vscode-spring-boot-dashboard)        | ![Rating](https://img.shields.io/visual-studio-marketplace/r/vscjava.vscode-spring-boot-dashboard)        | [预览](assets/spring-dashboard.gif) |
| [Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)     | K8s 集群管理和部署工具   | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-kubernetes-tools.vscode-kubernetes-tools) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-kubernetes-tools.vscode-kubernetes-tools) | [预览](assets/k8s.gif)              |

### 后端开发

#### Node.js

| 插件名称                                                            | 下载量                                                                 | 评分                                                                | 预览                   |
| ------------------------------------------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------- | ---------------------- |
| [Node.js](https://marketplace.visualstudio.com/items?itemName=Node.js) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Node.js) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Node.js) | [预览](assets/nodejs.gif) |

#### .NET/C#

| 插件名称                                                                     | 下载量                                                                               | 评分                                                                              | 预览                   |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- | ---------------------- |
| [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-dotnettools.csharp) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-dotnettools.csharp) | [预览](assets/csharp.gif) |

#### Java (Spring等)

| 插件名称                                                                                                    | 下载量                                                                                      | 评分                                                                                     | 预览                        |
| ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | --------------------------- |
| [Spring Boot Extension Pack](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-boot-dev-pack) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Pivotal.vscode-boot-dev-pack) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Pivotal.vscode-boot-dev-pack) | [预览](assets/spring-boot.gif) |

#### Ruby on Rails

| 插件名称                                                                                             | 下载量                                                                                            | 评分                                                                                           | 预览                          |
| ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ----------------------------- |
| [Ruby on Rails](https://marketplace.visualstudio.com/items?itemName=ruby-on-rails.vscode-ruby-on-rails) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ruby-on-rails.vscode-ruby-on-rails) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ruby-on-rails.vscode-ruby-on-rails) | [预览](assets/ruby-on-rails.gif) |

### 数据库

#### SQL

| 插件名称                                                                   | 下载量                                                                       | 评分                                                                      | 预览                     |
| -------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------------------ |
| [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/mtxr.sqltools) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/mtxr.sqltools) | [预览](assets/sqltools.gif) |

#### NoSQL

| 插件名称                                                                                       | 下载量                                                                                | 评分                                                                               | 预览                    |
| ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ----------------------- |
| [MongoDB for VS Code](https://marketplace.visualstudio.com/items?itemName=mongodb.mongodb-vscode) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/mongodb.mongodb-vscode) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/mongodb.mongodb-vscode) | [预览](assets/mongodb.gif) |

### 代码质量

| 插件名称                                                                                                     | 下载量                                                                                               | 评分                                                                                              | 预览                          |
| ------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ----------------------------- |
| [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)                   | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/SonarSource.sonarlint-vscode)          | ![Rating](https://img.shields.io/visual-studio-marketplace/r/SonarSource.sonarlint-vscode)          | [预览](assets/sonarlint.gif)     |
| [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/streetsidesoftware.code-spell-checker) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/streetsidesoftware.code-spell-checker) | [预览](assets/spell-checker.gif) |

### 远程开发

| 插件名称                                                                                                            | 下载量                                                                                                      | 评分                                                                                                     | 预览                       |
| ------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------- |
| [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-vscode-remote.vscode-remote-extensionpack) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-vscode-remote.vscode-remote-extensionpack) | [预览](assets/remote-dev.gif) |
| [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)                           | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/MS-vsliveshare.vsliveshare)                   | ![Rating](https://img.shields.io/visual-studio-marketplace/r/MS-vsliveshare.vsliveshare)                   | [预览](assets/live-share.gif) |

### 容器化开发

| 插件名称                                                                                                   | 下载量                                                                                                     | 评分                                                                                                    | 预览                       |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | -------------------------- |
| [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)                     | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-azuretools.vscode-docker)                 | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-azuretools.vscode-docker)                 | [预览](assets/docker.gif)     |
| [Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-kubernetes-tools.vscode-kubernetes-tools) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-kubernetes-tools.vscode-kubernetes-tools) | [预览](assets/kubernetes.gif) |

## 工具类扩展

### Git 相关

| 插件名称                                                                         | 下载量                                                                            | 评分                                                                           | 预览                      |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ------------------------- |
| [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)      | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/eamodio.gitlens)    | ![Rating](https://img.shields.io/visual-studio-marketplace/r/eamodio.gitlens)    | [预览](assets/gitlens.gif)   |
| [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/mhutchie.git-graph) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/mhutchie.git-graph) | [预览](assets/git-graph.gif) |

## 界面和美化

### 主题

| 插件名称                                                                                          | 下载量                                                                                        | 评分                                                                                       | 预览                           |
| ------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------ |
| [Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Equinusocio.vsc-material-theme) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Equinusocio.vsc-material-theme) | [预览](assets/material-theme.png) |
| [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/PKief.material-icon-theme)      | ![Rating](https://img.shields.io/visual-studio-marketplace/r/PKief.material-icon-theme)      | [预览](assets/material-icon.png)  |

## AI 辅助开发

| 插件名称                                                                              | 下载量                                                                                | 评分                                                                               | 预览                    |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ----------------------- |
| [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)     | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/GitHub.copilot)         | ![Rating](https://img.shields.io/visual-studio-marketplace/r/GitHub.copilot)         | [预览](assets/copilot.gif) |
| [Tabnine AI](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/TabNine.tabnine-vscode) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/TabNine.tabnine-vscode) | [预览](assets/tabnine.gif) |

### 代码重构工具

| 插件名称                                                                                               | 描述                               | 下载量                                                                                         | 评分                                                                                        | 预览                         |
| ------------------------------------------------------------------------------------------------------ | ---------------------------------- | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------------------- |
| [Refactor CSS](https://marketplace.visualstudio.com/items?itemName=urbantrout.refactor-css)               | CSS 代码重构和优化工具             | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/urbantrout.refactor-css)         | ![Rating](https://img.shields.io/visual-studio-marketplace/r/urbantrout.refactor-css)         | [预览](assets/refactor-css.gif) |
| [JavaScript Booster](https://marketplace.visualstudio.com/items?itemName=sburg.vscode-javascript-booster) | JavaScript/TypeScript 代码重构助手 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/sburg.vscode-javascript-booster) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/sburg.vscode-javascript-booster) | [预览](assets/js-booster.gif)   |

### 代码审查工具

| 插件名称                                                                                           | 描述                     | 下载量                                                                                           | 评分                                                                                          | 预览                         |
| -------------------------------------------------------------------------------------------------- | ------------------------ | ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | ---------------------------- |
| [Code Review](https://marketplace.visualstudio.com/items?itemName=d-koppenhagen.vscode-code-review)   | 代码审查管理和标注工具   | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/d-koppenhagen.vscode-code-review)  | ![Rating](https://img.shields.io/visual-studio-marketplace/r/d-koppenhagen.vscode-code-review)  | [预览](assets/code-review.gif)  |
| [Pull Request](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) | GitHub PR 审查和管理工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/GitHub.vscode-pull-request-github) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/GitHub.vscode-pull-request-github) | [预览](assets/pull-request.gif) |

### 项目管理工具

| 插件名称                                                                                        | 描述                    | 下载量                                                                                     | 评分                                                                                    | 预览                            |
| ----------------------------------------------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------- | ------------------------------- |
| [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) | 项目切换和管理工具      | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/alefragnani.project-manager) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/alefragnani.project-manager) | [预览](assets/project-manager.gif) |
| [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)             | TODO 注释管理和导航工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Gruntfuggly.todo-tree)       | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Gruntfuggly.todo-tree)       | [预览](assets/todo-tree.gif)       |

### 多语言支持

| 插件名称                                                                                | 描述               | 下载量                                                                                 | 评分                                                                                | 预览                        |
| --------------------------------------------------------------------------------------- | ------------------ | -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | --------------------------- |
| [i18n Ally](https://marketplace.visualstudio.com/items?itemName=Lokalise.i18n-ally)        | 国际化翻译管理工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Lokalise.i18n-ally)      | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Lokalise.i18n-ally)      | [预览](assets/i18n-ally.gif)   |
| [Translation](https://marketplace.visualstudio.com/items?itemName=hancel.google-translate) | 集成的翻译工具     | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/hancel.google-translate) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/hancel.google-translate) | [预览](assets/translation.gif) |

### 微服务开发

| 插件名称                                                                                                       | 描述                     | 下载量                                                                                                     | 评分                                                                                                    | 预览                             |
| -------------------------------------------------------------------------------------------------------------- | ------------------------ | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | -------------------------------- |
| [Spring Boot Dashboard](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-boot-dashboard) | Spring Boot 服务管理面板 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/vscjava.vscode-spring-boot-dashboard)        | ![Rating](https://img.shields.io/visual-studio-marketplace/r/vscjava.vscode-spring-boot-dashboard)        | [预览](assets/spring-dashboard.gif) |
| [Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)     | K8s 集群管理和部署工具   | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-kubernetes-tools.vscode-kubernetes-tools) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-kubernetes-tools.vscode-kubernetes-tools) | [预览](assets/k8s.gif)              |

### 移动应用开发

| 插件名称                                                                                            | 描述                    | 下载量                                                                                      | 评分                                                                                     | 预览                         |
| --------------------------------------------------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------- |
| [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)                       | Flutter/Dart 开发支持   | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Dart-Code.flutter)            | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Dart-Code.flutter)            | [预览](assets/flutter.gif)      |
| [React Native Tools](https://marketplace.visualstudio.com/items?itemName=msjsdiag.vscode-react-native) | React Native 开发工具包 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/msjsdiag.vscode-react-native) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/msjsdiag.vscode-react-native) | [预览](assets/react-native.gif) |

### 代码分析工具

| 插件名称                                                                                         | 描述                 | 下载量                                                                                          | 评分                                                                                         | 预览                        |
| ------------------------------------------------------------------------------------------------ | -------------------- | ----------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | --------------------------- |
| [CodeMetrics](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-codemetrics) | 代码复杂度分析工具   | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/kisstkondoros.vscode-codemetrics) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/kisstkondoros.vscode-codemetrics) | [预览](assets/codemetrics.gif) |
| [Code Time](https://marketplace.visualstudio.com/items?itemName=softwaredotcom.swdc-vscode)         | 编程时间统计分析工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/softwaredotcom.swdc-vscode)       | ![Rating](https://img.shields.io/visual-studio-marketplace/r/softwaredotcom.swdc-vscode)       | [预览](assets/codetime.gif)    |

### 代码生成工具

| 插件名称                                                                                                 | 描述               | 下载量                                                                                            | 评分                                                                                           | 预览                              |
| -------------------------------------------------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | --------------------------------- |
| [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)                      | 自动导入模块和组件 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/steoates.autoimport)                | ![Rating](https://img.shields.io/visual-studio-marketplace/r/steoates.autoimport)                | [预览](assets/auto-import.gif)       |
| [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) | 文件路径自动补全   | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/christian-kohler.path-intellisense) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/christian-kohler.path-intellisense) | [预览](assets/path-intellisense.gif) |

### 代码同步工具

| 插件名称                                                                                  | 描述                | 下载量                                                                                    | 评分                                                                                   | 预览                          |
| ----------------------------------------------------------------------------------------- | ------------------- | ----------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ----------------------------- |
| [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) | VSCode 配置同步工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Shan.code-settings-sync)    | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Shan.code-settings-sync)    | [预览](assets/settings-sync.gif) |
| [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) | 实时代码协作工具    | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/MS-vsliveshare.vsliveshare) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/MS-vsliveshare.vsliveshare) | [预览](assets/live-share.gif)    |

### 代码注释工具

| 插件名称                                                                                           | 描述               | 下载量                                                                                        | 评分                                                                                       | 预览                            |
| -------------------------------------------------------------------------------------------------- | ------------------ | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------- |
| [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)     | 增强的代码注释高亮 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/aaron-bond.better-comments)     | ![Rating](https://img.shields.io/visual-studio-marketplace/r/aaron-bond.better-comments)     | [预览](assets/better-comments.gif) |
| [Comment Anchors](https://marketplace.visualstudio.com/items?itemName=ExodiusStudios.comment-anchors) | 代码注释导航工具   | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ExodiusStudios.comment-anchors) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ExodiusStudios.comment-anchors) | [预览](assets/comment-anchors.gif) |

### 代码片段工具

| 插件名称                                                                                                      | 描述               | 下载量                                                                                    | 评分                                                                                   | 预览                         |
| ------------------------------------------------------------------------------------------------------------- | ------------------ | ----------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ---------------------------- |
| [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) | ES6+ 代码片段集合  | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/xabikos.JavaScriptSnippets) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/xabikos.JavaScriptSnippets) | [预览](assets/js-snippets.gif)  |
| [Vue 3 Snippets](https://marketplace.visualstudio.com/items?itemName=hollowtree.vue-snippets)                    | Vue 3 代码片段集合 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/hollowtree.vue-snippets)    | ![Rating](https://img.shields.io/visual-studio-marketplace/r/hollowtree.vue-snippets)    | [预览](assets/vue-snippets.gif) |

### 终端增强工具

| 插件名称                                                                            | 描述                | 下载量                                                                                | 评分                                                                               | 预览                       |
| ----------------------------------------------------------------------------------- | ------------------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | -------------------------- |
| [Terminal](https://marketplace.visualstudio.com/items?itemName=formulahendry.terminal) | 集成终端增强工具    | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/formulahendry.terminal) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/formulahendry.terminal) | [预览](assets/terminal.gif)   |
| [PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell) | PowerShell 集成支持 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ms-vscode.PowerShell)   | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ms-vscode.PowerShell)   | [预览](assets/powershell.gif) |

### 代码规范工具

| 插件名称                                                                                   | 描述                     | 下载量                                                                                   | 评分                                                                                  | 预览                         |
| ------------------------------------------------------------------------------------------ | ------------------------ | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ---------------------------- |
| [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) | 跨编辑器代码风格统一工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/EditorConfig.EditorConfig) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/EditorConfig.EditorConfig) | [预览](assets/editorconfig.gif) |
| [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)        | 代码格式化工具           | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/esbenp.prettier-vscode)    | ![Rating](https://img.shields.io/visual-studio-marketplace/r/esbenp.prettier-vscode)    | [预览](assets/prettier.gif)     |

### 文件管理工具

| 插件名称                                                                                        | 描述             | 下载量                                                                                     | 评分                                                                                    | 预览                            |
| ----------------------------------------------------------------------------------------------- | ---------------- | ------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------- | ------------------------------- |
| [File Utils](https://marketplace.visualstudio.com/items?itemName=sleistner.vscode-fileutils)       | 文件操作增强工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/sleistner.vscode-fileutils)  | ![Rating](https://img.shields.io/visual-studio-marketplace/r/sleistner.vscode-fileutils)  | [预览](assets/file-utils.gif)      |
| [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) | 项目管理工具     | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/alefragnani.project-manager) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/alefragnani.project-manager) | [预览](assets/project-manager.gif) |

### 代码调试工具

| 插件名称                                                                                                       | 描述                   | 下载量                                                                                               | 评分                                                                                              | 预览                             |
| -------------------------------------------------------------------------------------------------------------- | ---------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | -------------------------------- |
| [Debug Visualizer](https://marketplace.visualstudio.com/items?itemName=hediet.debug-visualizer)                   | 数据结构可视化调试工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/hediet.debug-visualizer)               | ![Rating](https://img.shields.io/visual-studio-marketplace/r/hediet.debug-visualizer)               | [预览](assets/debug-visualizer.gif) |
| [Debugger for Firefox](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug) | Firefox 浏览器调试工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/firefox-devtools.vscode-firefox-debug) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/firefox-devtools.vscode-firefox-debug) | [预览](assets/firefox-debug.gif)    |

### 代码覆盖率工具

| 插件名称                                                                                               | 描述               | 下载量                                                                                           | 评分                                                                                          | 预览                             |
| ------------------------------------------------------------------------------------------------------ | ------------------ | ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | -------------------------------- |
| [Coverage Gutters](https://marketplace.visualstudio.com/items?itemName=ryanluker.vscode-coverage-gutters) | 代码覆盖率显示工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ryanluker.vscode-coverage-gutters) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ryanluker.vscode-coverage-gutters) | [预览](assets/coverage-gutters.gif) |
| [Wallaby.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.wallaby-vscode)                | 实时测试覆盖率工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/WallabyJs.wallaby-vscode)          | ![Rating](https://img.shields.io/visual-studio-marketplace/r/WallabyJs.wallaby-vscode)          | [预览](assets/wallaby.gif)          |

### 代码优化工具

| 插件名称                                                                                                   | 描述               | 下载量                                                                                                | 评分                                                                                               | 预览                            |
| ---------------------------------------------------------------------------------------------------------- | ------------------ | ----------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | ------------------------------- |
| [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)                     | 显示导入包大小工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/wix.vscode-import-cost)                 | ![Rating](https://img.shields.io/visual-studio-marketplace/r/wix.vscode-import-cost)                 | [预览](assets/import-cost.gif)     |
| [Optimize Images](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-optimize-images) | 图片压缩优化工具   | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/fabiospampinato.vscode-optimize-images) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/fabiospampinato.vscode-optimize-images) | [预览](assets/optimize-images.gif) |

### 代码搜索工具

| 插件名称                                                                                                | 描述               | 下载量                                                                                         | 评分                                                                                        | 预览                           |
| ------------------------------------------------------------------------------------------------------- | ------------------ | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------ |
| [Search node_modules](https://marketplace.visualstudio.com/items?itemName=jasonnutter.search-node-modules) | 快速搜索依赖包工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/jasonnutter.search-node-modules) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/jasonnutter.search-node-modules) | [预览](assets/search-modules.gif) |
| [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)                     | TODO 注释搜索工具  | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/Gruntfuggly.todo-tree)           | ![Rating](https://img.shields.io/visual-studio-marketplace/r/Gruntfuggly.todo-tree)           | [预览](assets/todo-tree.gif)      |

### 代码对比工具

| 插件名称                                                                             | 描述             | 下载量                                                                             | 评分                                                                            | 预览                         |
| ------------------------------------------------------------------------------------ | ---------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | ---------------------------- |
| [Git History Diff](https://marketplace.visualstudio.com/items?itemName=huizhou.githd)   | Git 历史对比工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/huizhou.githd)       | ![Rating](https://img.shields.io/visual-studio-marketplace/r/huizhou.githd)       | [预览](assets/githd.gif)        |
| [Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff) | 文本选择对比工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/ryu1kn.partial-diff) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/ryu1kn.partial-diff) | [预览](assets/partial-diff.gif) |

### 代码统计工具

| 插件名称                                                                                    | 描述             | 下载量                                                                                  | 评分                                                                                 | 预览                           |
| ------------------------------------------------------------------------------------------- | ---------------- | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | ------------------------------ |
| [WakaTime](https://marketplace.visualstudio.com/items?itemName=WakaTime.vscode-wakatime)       | 编程时间统计工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/WakaTime.vscode-wakatime) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/WakaTime.vscode-wakatime) | [预览](assets/wakatime.gif)       |
| [VSCode Counter](https://marketplace.visualstudio.com/items?itemName=uctakeoff.vscode-counter) | 代码行数统计工具 | ![Downloads](https://img.shields.io/visual-studio-marketplace/d/uctakeoff.vscode-counter) | ![Rating](https://img.shields.io/visual-studio-marketplace/r/uctakeoff.vscode-counter) | [预览](assets/vscode-counter.gif) |

## 🤲 如何贡献

我们欢迎所有对 VSCode 和开发者社区感兴趣的朋友参与贡献：

1. 🎁 **提交插件**：如果你也有好用的插件分享，请通过 [Pull Request](https://github.com/wangruntao/awsome-vscode-zh/pulls) 提交你的插件信息，附上一句话说明，最好有gif图片。
2. 💡 **问题反馈**：在 [Issues](https://github.com/wangruntao/awsome-vscode-zh/issues) 中提出你的疑问、建议或问题。

---

🌟 感谢你的关注，期待大家一起贡献优质内容，让更多开发者受益！
