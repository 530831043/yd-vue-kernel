#ydweb
===

[![NPM version](https://badge.fury.io/js/yog.png)](http://badge.fury.io/js/yog) [![Dependencies Status](https://david-dm.org/fex-team/yog.png)](https://david-dm.org/fex-team/yog)

An express-based Node.js web application bootstrapping module, extends kraken-js.

### install

on Linux/Unix
```bash
$ npm install yog
```

on Windows

open a `cmd`

```bash
npm install yog
```

### use

```
.
├── app.js
├── config  # some `map.json` and `config.json`
├── controllers
├── lib
├── models
├── public # static
└── views # views or template
```

_app.js_

```javascript
var yog = require('yog');
var app = require('express')();
var PORT = 4000;

app.use(yog()).listen(PORT, function () {
    console.log('Listening *:' + PORT);
});
```

detail see project [fex-team/yog-app](https://github.com/fex-team/yog-app)

### others

+ [kraken-js](https://github.com/krakenjs/kraken-js)
+ [swig](https://github.com/paularmstrong/swig/)
+ [yog-view](https://github.com/fex-team/yog-view)
+ [yog-bigpipe](https://github.com/fex-team/yog-bigpipe)
+ [yog-swig](https://github.com/fex-team/yog-swig)
+ [yog-log](https://github.com/fex-team/yog-log)
=======
yog

===



\[!\[NPM version\]\(https://badge.fury.io/js/yog.png\)\]\(http://badge.fury.io/js/yog\) \[!\[Dependencies Status\]\(https://david-dm.org/fex-team/yog.png\)\]\(https://david-dm.org/fex-team/yog\)



An express-based Node.js web application bootstrapping module, extends kraken-js.



\#\#\# install



on Linux/Unix

\`\`\`bash

$ npm install yog

\`\`\`



on Windows



open a \`cmd\`



\`\`\`bash

npm install yog

\`\`\`



\#\#\# use



\`\`\`

.

├── app.js

├── config  \# some \`map.json\` and \`config.json\`

├── controllers

├── lib

├── models

├── public \# static

└── views \# views or template

\`\`\`



\_app.js\_



\`\`\`javascript

var yog = require\('yog'\);

var app = require\('express'\)\(\);

var PORT = 4000;



app.use\(yog\(\)\).listen\(PORT, function \(\) {

    console.log\('Listening \*:' + PORT\);

}\);

\`\`\`



detail see project \[fex-team/yog-app\]\(https://github.com/fex-team/yog-app\)



\#\#\# others



+ \[kraken-js\]\(https://github.com/krakenjs/kraken-js\)

+ \[swig\]\(https://github.com/paularmstrong/swig/\)

+ \[yog-view\]\(https://github.com/fex-team/yog-view\)

+ \[yog-bigpipe\]\(https://github.com/fex-team/yog-bigpipe\)

+ \[yog-swig\]\(https://github.com/fex-team/yog-swig\)

+ \[yog-log\]\(https://github.com/fex-team/yog-log\)


>>>>>>> 18d797b5d1bd22c22be5466c0033b7284bb13e83

