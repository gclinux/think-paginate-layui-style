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

