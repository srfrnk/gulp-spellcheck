# gulp-spellcheck [![Build Status](https://travis-ci.org/akoenig/gulp-spellcheck.svg?branch=master)](https://travis-ci.org/akoenig/gulp-spellcheck)

> A gulp plugin for spell-checking files.

## Usage

First, install `gulp-spellcheck` as a development dependency in your project.

```shell
npm install --save-dev gulp-spellcheck
```

Then, add it to your `gulpfile.js`:

```javascript
var spellcheck = require('gulp-spellcheck');

gulp.task('spellcheck', function () {
    gulp.src('./dododo/**/*.md')
        .pipe(spellcheck())
        .pipe(gulp.dest('./spellchecked/'));
});
```

## API

### spellcheck (options)

#### options

## Changelog

### Version 0.3.0 (Future)

- Ignore list

### Version 0.2.0 (Future)

- [ ] Update the README
- [ ] Better regexp for fetching words.
- [X] Improved readability.

### Version 0.1.2 (20140331)

- Added functionality for disabling 'pipe mode'.

### Version 0.1.1 (20140331)

- Fixed vinyl file access.

### Version 0.1.0 (20140331)

- Initial Release.

## Author

Copyright 2014, [André König](http://iam.andrekoenig.info) (andre.koenig@posteo.de)
