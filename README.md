# Expressjs Snippets

A collection of snippets for [Express.js](https://github.com/expressjs) for VSCode. To initiate, you can either use shorthand methods or type an express method and rest will be autocomplete.

- Supports es6 syntax
- Applicable upto Expressjs 4.x.x version

## Install
Press F1 and select Extensions: Install Extensions. Search for and select `expressjs`.

## Snippets

### Express API
- `app.all`
- `app.delete`
- `app.disable`
- `app.disabled`
- `app.enable` 
- `app.enabled`
- `app.get`
- `app.post`
- `app.put` 
- `app.listen` template
- `app.patch`
- `listen` app.listen(${1:port});
- `app.route `
- `app.set`
- `app.use`
- `res.json`
- `res.jsonp`
- `res.redirect`
- `res.render`
- `res.send`
- `res.status`
- `rss` res.status().send();
- `router`  express.Router() 
- `router.get`
- `router.apost`
- `router.put`
- `router.all`
- `router.delete`

**Initializing `app` variable**
- `app` const app = express ;

**Requiring Express**
- `express` const express = require('express');

**Requiring Express-Session**
- `session` const session = require('express-session');

### Commonly used Middleware
- `bodyParser.json` app.use(bodyParser.json );
- `bodyParser.url` app.use(bodyParser.urlencoded({extended: true}));
-` methodoverride` app.use(methodOverride('method'));
- `staticfile` app.use(express.static('public'));
- `compress` app.use(compression({level:zlib.Z_DEFAULT_COMPRESSION}));
- `helmet` app.use(helmet );
- `logger` app.use(logger );

#### Contribute
Pull requests for more snippets or any other issue(s) are welcome.

#### License
This software is released under the terms of the MIT license.