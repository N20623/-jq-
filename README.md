# webpackjQuery
同时提交给git仓库

使用 npm init -y  创建空白目录初始化package.json

新建src源代码目录  在该目录下新建  index.html

安装 cnpm install jquery -S 安装jQuery

通过模块化实现隔行变色的效果


#安装配置webpack

1.运行 cnpm install webpack webpack-cli -D  安装  webpack 相关的包

2.在根目录中创建
    在根目录中创建 webpack.config.js的文件
    webpack的配置文件 初始化基本配置
    module.exports = {
        mode:'development'  // mode 用来指定构建模式  开发模式不会压缩文件

    }
3.在终端运行 npm run dev  启动webpack进行项目打包

echo "# webpackjQuery" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/N20623/webpackjQuery.git
git push -u origin main

git remote add origin https://github.com/N20623/webpackjQuery.git
git branch -M main
git push -u origin main