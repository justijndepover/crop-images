# Crop Images

[![Latest Version on Packagist](https://img.shields.io/packagist/v/justijndepover/crop-images.svg?style=flat-square)](https://packagist.org/packages/justijndepover/crop-images)
[![Total Downloads](https://img.shields.io/packagist/dt/justijndepover/crop-images.svg?style=flat-square)](https://packagist.org/packages/justijndepover/crop-images)

## Installation
You can install the package with composer
```sh
composer global require justijndepover/crop-images
```

## Usage
```
crop [source] [width] [height] [-w, --whitespace]
```

This will generate a new folder in your current directory: `[width]x[height]` with all the cropped images from your source directory.

### Arguments
- source: The source directory
- width: The width of the new images
- height: The height of the new images
- whitespace: add whitespace around the images, defaults to false

If you provide one of the `width` or `height` arguments with `null`, only a resize will happen:
```sh
crop originals 1200 null
```
will generate images with a width of 1200 inside: `/1200x`, height is variable.

## Security
If you find any security related issues, please open an issue or contact me directly at [justijndepover@gmail.com](justijndepover@gmail.com).

## Contribution
If you wish to make any changes or improvements to the package, feel free to make a pull request.

## License
The MIT License (MIT). Please see [License File](LICENSE.md) for more information.