# express-content-type

content-type 無しで POST って受け取れるのか実験

## tl;dr

`"Content-Type": "application/json"` がないと body を parse できない。
body-parser がよし何やってくれるとかではなかった。

## dev

```
npm i

node index.js

open test.html
```
