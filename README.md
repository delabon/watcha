# Watcha

Focus on your code rather than your command line !

### Example 
in your watcha.settings.js
```javascript
exports.settings = {
    minify: true,
    js: {
        files : [
            '/assets/js/vendor/jquery.waypoints.js',
            '/assets/js/global.js',
            '/assets/js/animations.js',
            '/assets/js/navigation.js',
        ],
        dump_into: '/assets/js/front.js'
    },
    css: {
        files : [
            '/a.css',
            '/b.css',
        ],
        dump_into: '/c.css'
    },
    sass: [ '/assets/sass/style.scss', '/style.css' ]
};
```

### One command line to rule them all
```sh
$ node watcha
```

### Installation

```sh
$ cd watcha
$ npm install
```

### License

MIT Free Software, Hell Yeah!
