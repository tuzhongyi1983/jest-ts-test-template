1.创建项目文件夹

2.新建 src 文件夹，test 文件夹

3.npm 安装依赖
npm i -D jest typescript
npm i -D ts-jest @types/jest

4.初始化配置
npx ts-jest config:init
也可以直接拷贝 jest.config.js

5.创建 tsconfig
tsc --init
也可以直接拷贝 tsconfig.json

6.创建 Launch.json
Ctrl+Shift+D
然后添加配置
配置可以运行所有单元测试或只运行当前打开的指定文件。

7.运行单元测试
npm t or npx jest
也可以直接 F5 运行，进行调试。

8.测试代码编写
参见：
https://kulshekhar.github.io/ts-jest/user/test-helpers
https://github.com/microsoft/vscode-recipes/tree/master/debugging-jest-tests
JavaScript：https://jestjs.io/docs/en/getting-started.html
或其他 jest 单元测试说明文档。

注意：建议优先安装 TSLint 是 typescript 格式验证工具 1.安装
npm install -g tslint 2.初始化配置
tslint --init
建议使用推荐配置，请参见：tslint.json 3.此处所有的代码将被编译成 ES6 版本的 JavaScript，如果需要兼容 ESC2015+之前的 JavaScript 版本，请使用 Babel 工具链
Babel 是一个工具链，主要用于将 ECMAScript 2015+ 版本的代码转换为向后兼容的 JavaScript 语法

2019-11-21 TZY-1
