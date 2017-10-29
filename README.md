# \<random-list\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/ebabel-eu/random-list)

Returns the subset of a list of x elements from a larger source list.

## Installation

```
bower install --save ebabel-eu/random-list
```

## Usage

```
const rainbow = [ 'red', 'orange', 'yellow', 'green', 'blue', 'indigo', 'violet' ];
<random-list source="[[rainbow]]" max="3"></random-list>
```

this component picks 3 random colors from the rainbow list:

```
[ 'orange', 'blue', 'violet' ]
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

- 0.1.0 is a pre-release setup

## License

GPL-3.0
