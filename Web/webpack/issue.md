#### [Error: No PostCSS Config found in...](https://www.cnblogs.com/sichaoyun/p/8243273.html)

在项目根目录新建**postcss.config.js**文件，并对**postcss**进行配置：

```
module.exports = { 
  plugins: { 
    'autoprefixer': {browsers: 'last 5 version'} 
  } 
}
```



