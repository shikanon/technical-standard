# technical-standard

技术规范，主要包括版本管理、CI/CD、团队管理等各类的技术规范。

## 版本控制/代码审核

版本库有两条主要分支：Master和dev。前者用于正式发布，后者用于日常开发。

除了常设分支以外，还有一些临时性分支，用于应对一些特定目的的版本开发。临时性分支主要有三种：
- 功能（feature）分支
- 预发布（pre-release）分支
- 修补bug（fixbug）分支
  
[版本控制详细说明](./版本控制/版本控制.md)

## 版本管理规范

[版本管理规范](./git版本管理规范.md)

## 交付文档规范

[交付文档模板](./交付文档规范)

## CI/CD规范

gitlab CI 操作示例的步骤：
https://docs.gitlab.com/ee/ci/quick_start/#creating-a-simple-gitlab-ciyml-file

### 编写 gitlab-ci.yaml 文件

gitlab-ci.yaml 语法规范：
https://docs.gitlab.com/ee/ci/yaml/

## 代码规范参考

- [Python代码编写规范](./代码规范/Python代码编写规范.md)
- [前端代码编写规范](./代码规范/JavaScript代码编写规范.md)

## 系统设计规范

- [日志系统设计规范](./系统设计规范/日志系统设计规范.md)