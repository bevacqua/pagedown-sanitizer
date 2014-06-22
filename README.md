# pagedown-sanitizer

> PageDown sanitizer

## Fetch

    $ npm install pagedown-sanitizer --save

## Use

    var marked = require('ultramarked');
    var sanitizer = require('pagedown-sanitizer');

    marked.setOptions({
        sanitizer: sanitizer
    });

    marked('This is **awesome**!');

## License

MIT
