# jQuery-finder

This library implements a finder game where users need to locate and click on specific targets within a grid layout within a time limit.

## Installation

Import directly in html file.

``` html
<!-- HTML -->

<link href="path/jQuery-finder/finder.css" rel="stylesheet">
<script src="path/jQuery-finder/finder.js"></script>
```

## Usage

### Library settings

``` bash
# Edit default style
vi path/jQuery-finder/finder.css

# Edit default setting
vi path/jQuery-finder/finder.js
```

### How to use

``` html
<!-- HTML -->

<!-- Add data attribute "WKFINDER" to your game container -->
<div data-game="WKFINDER"></div>
```

``` javascript
<!-- JavaScript -->

// Initialize the finder game
$('[data-game="WKFINDER"]').WKFinder();
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
