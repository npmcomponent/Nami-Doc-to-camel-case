*This repository is a mirror of the [component](http://component.io) module [nami-doc/to-camel-case](http://github.com/nami-doc/to-camel-case). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/nami-doc-to-camel-case`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# to-camel-case

  Converts a string to camelCase

## Installation

    $ component install Nami-Doc/to-camel-case

    $ npm install to-camel-case

## API

### toCamelCase(string, first = false)

```js
toCamelCase("hello-ya").should.equal("helloYa")

toCamelCase("chocolate-rain").should.equal("chocolateRain")

toCamelCase("hello-howare-ya", true).should.equal("HelloHowareYa")
```

## License

  MIT
