## Static Page Design

此项目作为早期的静态页面快速架构.


## 说明

此项目使用 grunt 的 LiveReload ,也就是修改模板和 js , scss
文件的时候会自动刷新浏览器, 对于有多屏幕的开发, 很省事, 并且会自动编辑
scss .

在 yeoman 的generator-webapp 基础上, 添加了 jade 的模板引擎,
允许文件划分更加灵活. 


## 技术清单

* 使用 [Yeoman](http://yeoman.io) 来提高静态页面的代码编写效率. 
    * grunt
    * bower
    * livereload
* Jade 模板引擎

## Setting UP

clone 代码

    git clone git@github.com:guhuina/blog-design.git

安装 pakages 

    npm install 

安装 components

    bower install 

可以开始了

    grunt serve

