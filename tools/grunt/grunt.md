# Grunt
Grunt的使用难度不算很简单，但也不会太难。Grunt本身没有太多困难之处，只是配置你所需要的工具可能会花费你一定的时间。但是，这种时间花费是值得的，当你配置好工具后，那些工具就会自动地为你服务，减少你的劳动。
   

### 配置Grunt前的工作
Grunt插件与其它node模块一样，需要在用之前引入进来。一般来说，是在package.json里的devDependecies里面写上你需要用到的插件名字。如：
 ```
    "devDependencies": {
      "grunt": "~0.4",
      "grunt-contrib-jshint": "~0.3.0",
      "grunt-contrib-uglify": "*"
    }
 ```

在引入之后，使用`npm install`就会安装你所需要的插件模块。
   

### Gruntfile.js





