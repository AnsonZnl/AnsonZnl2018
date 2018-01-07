## webpack 安装过程
* npm install vue
* 安装 vue（也可用于bt jQ zepot jQ mobile）
* 淘宝镜像安装cnpm
* $ npm install -g cnpm --registry=https://registry.npm.taobao.org
* npm install -g cnpm
* 安装cnpm 
* 安装webpack(打包工具)
* cnpm install -g webpack 
* 安装 webpack-dev(虚拟服务器)
* cnpm install -g webpack-dev-server
* 肯错+c =从新启动
* 新建配置js文件 
 * G:\xinjian
 *新建一个index.html main.js webpack.config.js
* main.js 正常输入代码
* 在webpack.config.js中配置新建的js
*  如下:
```
module.exports={
    entry:"./main.js",
    //同级加.///同级加./
    output:{
        filename:"bik.js"
    }
    //导出的文件名
};

```


* 在新建的文件打开Git Bash
* 输入webpack
* 会新建一个 自己命名的js

* 压缩 js 
*webpack -p*
