# web2web-lib
Create your own distributed webpage. Take a look at the original [web2web](https://github.com/elendirx/web2web) concept.


### Install
Web2web is a browser library. Download the minified `web2web.min.js`.

Alternatively you can [browserify](http://browserify.org) it by yourself:

    npm install web2web-lib
    

### API
#### Load webpage from btc address
```javascript
var btcAddress = '1DhDyqB4xgDWjZzfbYGeutqdqBhSF7tGt4'
var web2web = new Web2Web()
web2web.bootstrap(btcAddress)
```

#### Load webpage from torrent info hash
```javascript
var infoHash = 'acaa4ece96da0e31f2bd7f1e4d82f4e1317e2af7'
var web2web = new Web2Web()
web2web.bootstrap(infoHash)
```