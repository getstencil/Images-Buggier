# Buggie

This repo contains image-files that may cause issues in systems that run
operations against them.

For example, it contains some images that will break when attempting to use
`ImageMagick` to convert the quality, and SVG images that will fail when an
attempt to rasterize them is made.

The goal of this library is to slowly grow it's list of test-images so that you
can ensure your image processing system is working reliably (eg. for unit
tests).
