# Metanuker

A simple bash script to remove metadata from image files using exiv2 **(Requires exiv2 to be installed)**

## Installation

- Make it executable
```
chmod +x metanuker
```

- Move it to your PATH (optional)

```
sudo mv metanuker /usr/local/bin/
```

## Usage

- Removes metadata from a single image file

```
metanuker image.png
```

- Removes metadata from all suitable image files in a directory

```
metanuker -f /path/to/
```
