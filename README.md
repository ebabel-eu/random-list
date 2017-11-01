# \<random-list\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/ebabel-eu/random-list)

Returns the subset of a list of x elements from a larger source list.

## Installation

```
bower install --save ebabel-eu/random-list
```

## Usage

```
<random-list id="rainbowList"></random-list>
```

In a script where random-list is accessible, call its function pickRandomList:

```
const result = this.$.rainbowList.pickRandomList({
  source: [ "red", "orange", "yellow", "green", "blue", "indigo", "violet" ],
  max: 3,
});
```

this component picks 3 random colors from the rainbow list:

```
result.list is [ "orange", "blue", "violet" ]
result.rest is [ "red", "yellow", "green", "indigo" ]
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

- 1.0.0 works and is the first release
- 0.3.0 works but not documented yet
- 0.2.0 is also a pre-release version
- 0.1.0 is a pre-release setup

## License

GPL-3.0
