# css-cleaner
在一堆文件中找出用到了该样式表样式的文件。
## cleaner(cssPath, searchDir)
如果 `searchDir` 包含 `cssPath` , `cssPath` 将会忽略.
## demo
```js
const cleaner = require('./css-cleaner');
cleaner('src/css/style.css', 'src');
```