### duo
---
https://github.com/duojs/duo

```
npm install -g duo
duo index.js
duo index.css

DEBUG=duo* $COMMAND
DEBUG=duo* duo index.js
make test
```

```js
var uid = require('matthewmueller/uid');
var fmt = require('yeilds/fmt');
var msg = fmt('Your unique ID is %s!', uid());
window.alert(msg);

```

```
<script src="build/index.js"></script>

<link rel="stylesheet" href="build/index.css">
```

```
// ~/.netrc
machine api.github.com
  login <username>
  password <token>
```


