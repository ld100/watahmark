# Photo Shit / Watahmark Application

Resizes and watermarks photos for public access

## Prerequisites

* ImageMagick
* GhostScript

On Mac:

`brew install ghostscript imagemagick graphicsmagick`
`bundle install`

On Linux:
`sudo apt-get install imagemagick`
`bundle install`

## Running the Application

Process photos in Source directory:

`rake process`


Clean up Destination directory:

`rake cleanup`