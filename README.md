
# Responsive Website Viewer
A web-based tool that allows you to preview websites across multiple screen resolutions simultaneously. Perfect for responsive design testing and cross-resolution compatibility checks.

## Features

### Multiple Resolution Support: Preview websites in various common screen resolutions:

* Desktop resolutions (8K to HD)
* Tablet resolutions
* Mobile device resolutions
* Custom resolution support

### Synchronized Browsing:

* Synchronized scrolling across all viewports
* Synchronized link clicking
* Cross-viewport navigation

### Resolution Presets:

* 8K (7680x4320)
* 5K (5120x2880)
* 4K (3840x2160)
* Ultrawide (3440x1440)
* QHD (2560x1440)
* Full HD (1920x1080)
  And many more standard resolutions

### Custom Features:

* Add custom resolution viewports
* Loading indicators
* Viewport labels
* Responsive layout
* Cross-origin handling

## Usage

* Open the HTML file in a web browser
* Enter a website URL in the input field (e.g., https://example.com)
* Select desired screen resolutions from the preset buttons
* Click "Load" to view the website in all selected resolutions

### Adding Custom Resolutions

* Enter desired width (min: 200px)
* Enter desired height (min: 200px)
* Click "Add" to create a new resolution preset

## Technical Details

* Pure vanilla JavaScript implementation
* No external dependencies
* Handles cross-origin restrictions gracefully
* Responsive design with CSS Grid and Flexbox
* Supports modern browsers (Chrome, Firefox, Safari, Edge)

## Limitations

* Crss-origin restrictions may limit functionality for some websites
* Some websites may block iframe embedding
* Performance may vary with multiple high-resolution viewports

## Browser Support

* Chrome (latest)
* Firefox (latest)
* Safari (latest)
* Edge (latest)

## License
MIT License

## Contributing

Feel free to submit issues and enhancement requests!

To use this tool, simply download the HTML file and open it in your web browser or open the github static pages website of this [page](https://muralinunna.github.io/resolutions-viewer/).
