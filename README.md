# Convert images and videos easier

`media-converter` is a simple Shell script that tries to make the converting process using FFMpeg much simpler, by omitting all the details on compression codecs and bulk conversion.

## Features

- **Single or Bulk Conversion**: Convert all files with `.ext1` to `.ext2`, or a single file.
- **Compression made easy**: Compression without caring about codecs.

## Installation

```bash
git clone https://github.com/aocoronel/media-converter-sh.git
chmod +x media-converter-sh/src/media-converter
sudo cp media-converter-sh/src/media-converter /usr/local/bin/
```

## Usage

```
Bulk Media Converter

Usage:
  media-converter FLAG <FLAG_INPUT> COMMAND INPUT
  media-converter -h | media-converter help

Commands:
  bulk                        Convert media files in bulk
  help                        Displays this message and exits
  single                      Convert a single file
  version                     Display current version

Flags:
  -b                          Define a bitrate (default: 128k)
  -h                          Displays this message and exits
  -s                          Skip overwrite dialog
  -v                          Display current version
  -w                          Remove input files
```

## License

This repository is licensed under the MIT License, a very permissive license that allows you to use, modify, copy, distribute and more.
