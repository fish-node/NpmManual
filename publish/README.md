## 发布一个包
相关的字段
- name： 必填，表明我们的包名。需要在npmjs上唯一，记得提前到npm官网上搜索一下
- version： 必要，每次上传这个值只能增加，不能不变或者减少。
- homepage: 尽量填写，一般就是github地址，这样如果别人对我们的项目有兴趣，就可以找到地方。
- main：尽量填写，是别人在require你的模块的时候的查找路径。不写就是index.js

## .npmignore
如果没有这个字段，就使用`.gitignore`。

## publish
在官网上注册一个账号，然后
```
npm login
npm publish
```
就行了。

注意： 如果之前使用过taobao等镜像，publish的时候要设置回来，不然没有权限。