# sojs.utility
===================================
sojs工具库. 
轻量级类库直接放在 sojs.utility 项目中.
复杂的类库比如 sojs.utility.file, sojs.utility.url 等作为单独项目维护.
使用时, 只需要引用 sojs.utility 即可.由sojs.utility负责加载其他子项目.

---

# Install
```
npm install sojs-utility
```

# Use
```

require('sojs-utility');

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
