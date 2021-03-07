# ImgOptimize

ImgOptimize uses tools to optimize images and reduce file size.

## Install

ImgOptimize is a bash script and can be run directly. You can install it by copying the `imgoptimize` file to your `PATH`. Example:

```sh
wget -O /usr/local/bin/imgoptimize https://github.com/eduardoklosowski/imgoptimize/raw/main/imgoptimize
chmod +x /usr/local/bin/imgoptimize
```

Depending on the image format, external tools are required. You can check
external tool at [Supported Format](#supported-formats).

## Supported Formats

| Format | External Tool |
| ------ | ------------- |
| GIF    | [gifsicle](https://www.lcdf.org/gifsicle/) |
| JPEG   | [jpegoptim](https://github.com/tjko/jpegoptim) or [jpegtran](https://libjpeg-turbo.org/) |
| PNG    | [optipng](http://optipng.sourceforge.net/)

## Example of Use

Run `imgoptimize` with images as arguments. One or more images can be entered.

```sh
imgoptimize file.jpg
imgoptimize file.gif file.jpg file.png
```
