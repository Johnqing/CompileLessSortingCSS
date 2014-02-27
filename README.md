编译less，然后整理css
=====================

根目录下，防止该项目中的文件，

修改 `feBuild.js` 中的 配置项 

```
var defConf = {
    "encode": "utf-8",
    "workspace": "./src/www/front/resource/",
    "ignore": 'combo',
    "input":  "css",
    "lessInput": "other/less"
}

```

运行

```
npm install
node feBuild
```