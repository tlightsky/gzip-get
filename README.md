# gzip-get

var gzip_get = require('gzip-get');
gzip_get(url, function(err, data) {
    if (err) console.log(err);
    else console.log(data);
});
