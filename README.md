# Bower endpoint

This is a bower endpoint for jspm.

To add bower as a jspm repository:
```shell
npm install -g jspm-bower
jspm registry create bower jspm-bower
```

Then, To install a package just reference it by the package name, for example:
```shell
jspm install bower:jquery@1.9.1
```

Will install jquery version `1.9.1`. You can also require packages and use them directly in your code:

```javascript
var gazel = require('bower:gazel');
```
