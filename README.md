# Web Fundamentals

### Contributing

We love contributors!

This project uses Yeoman (because I'm lazy) and Zurb Foundation 5 (because I'm lazy).

Dependencies:

* Nodejs
* NPM
* Bower

Grunt tasks:

run project
(compile Jade, compile Sass, bower install, livereload (server on 127.0.0.1:9000), watch)
```
$ grunt
```
publishing project (into dist directory)
(compile Jade, compile Sass, validate-js, copy, concatenation, minifications)
```
$ grunt publish
```
dist directory preview (server on 127.0.0.1:9001)
```
$ grunt server-dist
```

More information here: https://github.com/juliancwirko/generator-zf5

### Deploying the app

Just push the dist folder to gh-pages branch.

```
git subtree push --prefix dist origin gh-pages
```



