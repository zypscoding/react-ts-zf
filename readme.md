# 0 
npm i typescript webpack webpack-cli webpack-dev-server ts-loader cross-env webpack-merge clean-webpack-plugin html-webpack-plugin -D
安装eslint npm i eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser -D
单元测试
 npm i jest @types/jest ts-jest -D
npx ts-jest config:init (npm自5.2带npx,node自带npm,可直接用npx,不能则npm i -g npx)
## 1 ts的编译方式
- ts-loader 编译的时候可以进行类型检查
- babel-loader @babel/preset-typescript 不能进行类型检查

