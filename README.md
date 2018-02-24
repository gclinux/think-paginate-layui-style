介绍:
关于layui : http://www.layui.com/
关于thinkphp : http://www.thinkphp.cn

layui是一个前端解决方案,目的是以最简单的方式让后端人员解决前端问题. 与其他框架不一样,它提供的并不只是框架,而是是一种打包的解决方案,这个方案包各种常见的插件都以最简单和通用的方式展现,节约时间,而且与其他框架不冲突.

thinkphp5 是一个轻量级的面向api开发的后端php框架,可以说与laravel5有参考地方,但实现方面更轻量级,更灵活.

本插件是解决tp5只内置bootstrap的分页方式,如果你只是想用TP自带的mvc的模版方式输出而不想用MVVC方式,想结合layui又不想用bootstrap时候,这个模块能帮助你用最tp的方式输出layui的css分页方式.

安装方法:
```
conposer require gclinux/think-paginate-layui-style
```
使用方法:

修改您的配置文件,默认为应用目录下的 config.php

把分页里'type'      => 'bootstrap',改为 type=>'Layui';

例如:

```
//分页配置
    'paginate'      => [
        'type'      => 'Layui',
        'var_page'  => 'page',
        'list_rows' => 15,
        'newstyle'  => true,
    ],
```

