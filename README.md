## 小程序代码压缩
- 当我们使用小程序来进行开发的时候，最终需要对代码进行优化，微信虽然有自带的小程序压缩，可是个人感觉效果并不理想，于是使用gulp写了一个压缩的方案。

## 优点
1. 支持所有的ES6语法转换
2. 使用postcss与autoprefixer实现css样式的兼容

## 使用
1. 将.babelrc、gulpfile.babel.js以及package.json拷贝到你的项目的根目录
2. 使用npm install安装所需要的依赖
3. 使用gulp prod命令来进行代码的压缩