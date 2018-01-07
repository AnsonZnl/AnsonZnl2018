
### vue-cli 模板使用
* vue-cli脚手架 模板 通过命令行 自动创建模板（indec.html .js .css）
* vue-cli的github项目网址 [vue-cli github](https://github.com/vuejs/vue-cli) 详细介绍点击可查看
* 使用淘宝镜像cnpm ``npm install cnpm -g`` 
* 使用cnpm安装vue ``cnpm install -g vue-cli``  安装vue-cli
* 通过 ``vue --version`` 查看vue版本 返回版本号则操作正确
* 通过``vue list`` 查看vue-cli 模板

### vue-cli 的六种模板 Available official templates:

 *  ★  browserify - A full-featured Browserify +            vueify setup with hot-reload, linting & unit            testing.
 -  ★  browserify-simple - A simple Browserify +            vueify setup for quick prototyping.
 -  ★  pwa - PWA template for vue-cli based on t           he webpack template
 -  ★  simple - The simplest possible Vue setup            in a single HTML file
 -  ★  webpack - A full-featured Webpack + vue-l           oader setup with hot reload, linting, testing            & css extraction.
 -  ★  webpack-simple - A simple Webpack + vue-l           oader setup for quick prototyping.

-  vue init <template-name>（模板名 如：webpack-simple） <project-name>（项目名字 如：my-project）;
如 :``vue init webpack-simple my-project``
然后 一直回车 有作者信息和sass 描述等
- 进入到你的文件中``cd my-project``
- 下载所需要的依赖``cnpm install`` （依赖最后有对勾就是对了 不对的话重新删除在下载一次）
- 开启虚拟服务器``cnpm run dev`` 如果操作正确的话会自动弹出浏览器
- 返回上一级``cd ..``
