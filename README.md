# log-with-colors
Log with colors is a simple syntax to colored console log, based on [chalk](https://github.com/chalk/chalk)
```javascript
log.green('This will log to console in green')
```
![](https://github.com/al-lopes/log-with-colors/blob/master/README.png?raw=true)

## Install

```console
$ npm i -S log-with-colors
```

## Usage

```javascript
const log = require('log-with-colors')
```
```javascript
log.success('Hello World') //logs to the console in green
```

## API

| Function      | Type          | Info          |
| ------------- |:-------------:|:-------------:|
| log()         | default       | Prints with process.stdout |
| log.error()   | error         | Prints with process.stderr |
| log.success() | color         | Equals to log.green()   |
| log.warn()    | color         | Equals to log.yellow()  |
| log.info()    | color         | Equals to log.cyan()    |

| Function      | Type          |
| ------------- |:-------------:|
| log.gray()    | color         |
| log.blue()    | color         |
| log.cyan()    | color         |
| log.green()   | color         |
| log.yellow()  | color         |
| log.red()     | color         |
| log.magenta() | color         |

## License
MIT © [Alexandre Lopes](https://alexandrelopes.design)
