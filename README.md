# Riffusion Reverse API
The Riffusion API provides a convenient way to generate music with lyrics using Riffusion.

## Installation

To use this package, you'll need to install it and its dependencies. You can do this with pip:

```bash
pip install riffusion
```

## Usage
Here's a basic example of how to use this package to generate a song:
```py
from riffusion.riff import sing

# Define your lyrics and style
lyrics = "Hey guys, how's it going"
style = "Pop"

# Generate audio and visual variations
sing(lyrics, style)
```

## Dependencies
This package relies on several external libraries:

* requests: for making HTTP requests to the Riffusion API.
* json: for working with JSON data.
* base64: for decoding base64-encoded data.
* os: for file and directory operations.
* moviepy: for video and audio editing.
Make sure to install these dependencies along with the package.

### Please note, this is not an official package or API