# Introduction
This is a collection of scripts for the Caja file manager. These scripts can be installed to `${XDG_CONFIG_HOME}/caja/scripts`. They can be run on files or directories when right-clicked.

# Scripts
## unzip
Unzips one or more zip archives to the current directory.

## img-cw
Rotates a single image clockwise.

## img-ccw
Rotates a single image counter clockwise.

## img-flip
Flips a single image.

## img-trim
Uses [Trim Pictures](https://github.com/krithin/trimpictures) to automatically trim and deskew scanned images. The Python script should be compiled to a single binary called '.img-trim' using Nuitka.

## ocr
Takes one or more images, runs optical character recognition using [Tesseract](https://github.com/tesseract-ocr/tesseract), and consolidates the images into a single document using filename for page order.

## fly
The fly script will reconsolidate video files recorded from a [Fly6 Original](https://cycliq.com/support/fly6-original/). The files are split into 10 minute segments with 2 seconds of overlapping footage between files. The file and directory naming scheme allows you to infer the date, timestamp, and segment. These files are then recombined into a single file using the ISO 8601 format.
