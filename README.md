# React 前端工程脚手架

- 支持 SCSS
- 支持 React hot loader
- 支持 ESLint
- babel 7
- webpack 4

## 使用

先安装 babel cli, 确保 babel 版本为 7

```shell
npm i @babel/core @babel/node @babel/cli -g

babel -v # -> 7
babel-node -v # -> 7
```

```shell
git clone https://github.com/SANGET/react-app-seed.git yourProjectName
cd yourProjectName
npm run init
```

## 代码规范约定

Step1. 安装 ESLint 开发环境

```shell
yarn add eslint eslint-config-airbnb eslint-plugin-node eslint-plugin-promise eslint-plugin-react --dev -W
```

Step2. vscode 安装 eslint 插件

Step3. 使用 .eslintrc 文件