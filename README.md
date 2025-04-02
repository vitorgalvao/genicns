# GenICNS 

GenICNS is a command-line tool to create an [Apple Icon Image format](https://en.wikipedia.org/wiki/Apple_Icon_Image_format) file (`.icns`) from a [Portable Network Graphics](https://en.wikipedia.org/wiki/PNG) file (`.png`).

## Installation

Install with [Homebrew](https://brew.sh):

```shell
brew install vitorgalvao/tiny-scripts/genicns
```

Alternatively, download the executable at the root of this repository and call it directly.

## Usage

```
Generate an icns file from a png.

Usage:
  genicns --input <file> --output <file>

Options:
  -i, --input <file>    File to convert.
  -o, --output <file>   File to save.
  -h, --help                 Show this message.
```

## License

3-Clause BSD
