# Grunt   
 The JavaScript Task Runner.
   
## Index
1. [简介](#intro)
2. [Grunt是什么](#gruntis)
3. [Grunt不是什么](#gruntisnot)
4. [Grunt的安装](#gruntinstall)
4. [Grunt的用法](#gruntusage)

   
## 简介
Grunt是一个基于Node.js的自动化任务管理器(Task Runner)。它自身并没有提供太多的功能，但依靠大量的插件，提供了许多功能。如果上面没有你想要的插件，你也可以通过它的模板，去实现你想要的插件。   
Grunt分为grunt、grunt-cli、grunt-init。   
grunt-cli用于在命令行中启动grunt。   
grunt-init用于以命令行形式新建Grunt插件模板。   
    
    
## Grunt是什么
Grunt 是一个应用程序构建、任务管理工具。它可以实现生产自动化，避免大理繁琐单调重复的工作。
   

   
## Grunt不是什么
Grunt自身并不具体实现某个功能(如压缩代码), 它并不能代替你写代码，也不能代替你的测试。
   
   
## Grunt安装
Grunt在v0.4后分为三个模块，需要分别安装。
* grunt-cli
  grunt-cli是在命令行启动grunt必不可少的东西。它安装时候必须作为全局模块安装。
* grunt-init
  grunt-init是一个可选的模块。一般单纯地使用grunt可能用不到这个模块。它用于命令行创建Grunt项目模板。它也必须使用全局方式来安装。
* grunt
  grunt这个功能模块在项目的package.json里添加后，使用npm安装即可。
   
   
## Grunt的用法
 参见[Grunt Usage](./grunt.md)











