- `yarn init`
- `yarn add babel babel-cli babel-core babel-preset-es2015`
- `yarn run dev`
```
➜  require_vs_import: yarn run dev
yarn run v1.2.0
$ babel src -d dist && node dist/main.js
src/a.js -> dist/a.js
SyntaxError: src/main.js: Unexpected token, expected ; (1:4)
> 1 | jar a0 = require('./a.js');
    |     ^
  2 | import a1 from './a.js';
  3 | a0++
  4 | a1++
error Command failed with exit code 1.

```

- ref: [Can I use es6 style module import in nodejs application
](https://stackoverflow.com/questions/41338620/can-i-use-es6-style-module-import-in-nodejs-application)
- ref: https://www.zhihu.com/question/56820346/answer/150772385
