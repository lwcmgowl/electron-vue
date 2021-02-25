# electron-vue

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
# electron-vue

打包时,如果是中文目录,需要: 
  修改文件
  ```
  node_module/app-builder-lib/out/targets/nsis/NsisTarget.js ```的 ```executeMakensis```方法
  增加
  ```
  args.push("-INPUTCHARSET", "UTF8");
  ```
