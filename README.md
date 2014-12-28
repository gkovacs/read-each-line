# read-each-line-sync

Read file line by line, synchronously.

## Install

    npm install read-each-line

## Example

    var readEachLine = require('read-each-line')
    
    readEachLine('test.txt', 'utf8', function(line) {
      console.log(line)
    })

Encoding can optionally be omitted, in which case it will default to utf8:

    readEachLine('test.txt', function(line) {
      console.log(line)
    })

## Credits

Author: [Geza Kovacs](http://github.com/gkovacs)

Based on [readLineSync](https://gist.github.com/Basemm/9700229)

## License

MIT
