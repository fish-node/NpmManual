## 安装包 
```
npm i fish-npm@version
npm install fish-npm
npm i fish-npm -D
```

为了记录我们安装过哪些依赖，方便其他人clone我们的项目。这个命令会自动把依赖关系写到 package.dependencies 或者package.devDependencies中。

上述两者都是表明依赖关系，只是语义化不同。前者表明在程序运行时的依赖，后者是构建时的依赖。

`>0.0,1`是告诉npm应该安装更高的版本，你用这个时候必须很小心，因为别人使用的依赖版本可能和你的代码不兼容。
