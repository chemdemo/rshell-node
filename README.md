# wts-node
[![NPM version](https://badge.fury.io/js/wts-node.png)](https://npmjs.org/package/wts-node)

Node.js client for [WTS system](https://github.com/chemdemo/wts-monit).

### Usage

- install

``` bash
npm install wts-node && npm i
```

or just clone from github:

``` bash
git clone https://github.com/chemdemo/wts-monit.git
```

- config

``` bash
cd wts-node && vim conf.js # you should assign group for one client.
```

- launch with debug mode

``` bash
node index.js
```

- deploy(via pm2)

``` bash
pm2 start pm2_deploy.json
```

### License

Copyright (c) 2015, chemdemo (MIT License)
