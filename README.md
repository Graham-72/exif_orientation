# Exif Orientation

This simple module reads EXIF data and rotates images that have an 
Orientation Key set. 

The module solves the issue where images are produced by digital 
cameras containing rotation sensors and produce image files 
with an EXIF Orientation value. Modern applications may then 
automatically rotate the image so that it appears in its correct 
orientation but if uploaded to a web server it will not be correct. 
This module adds the necessary rotation to the upload process.

This is a port to Backdrop of the Drupal module v7.x-1.2.

## Installation

Follow the usual Backdrop CMS procedure.

## Configuration

No configuration is necessary.

## License

This project is GPL v2 software. See the LICENSE.txt file in this
directory for complete text.

## Credits

### Port to Backdrop

+ Graham Oliver (github.com/Graham-72)

### Developer for Drupal:

+ Matt Glaman (mglaman)
