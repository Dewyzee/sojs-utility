# sojs.utility.file
===================================
文件操作工具类

---

# Install
```
npm install sojs-utility-file
```

# Use
```
require('sojs');
require('sojs-utility-file');

var file = sojs.using('sojs.utility.file');
var filePath = sojs.getClassPath('sojs.utility.file');
file.readFileSync(filePath);
```

# Develop

## install for develop
```js
npm install
```

## Unit Test
```js
node .\tool\unit.js
```

## Benchmark
```js
node .\tool\benchmark.js
```

## Coverage
```js
node .\tool\coverage.js
```
