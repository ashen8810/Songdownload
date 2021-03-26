![Python 3.5, 3.6, 3.7](https://img.shields.io/pypi/pyversions/vk_songs.svg)

# Songsdownload
songsdownload is written in Python that downloads sinhala songs and lyrics files.

## Features
--------
- Download Sinhala MP3 songs
- Download Lyrics Files
- Download Array of Songs
--------
## Installation
```pip install songsdownload```

## How to use it?
```python 
from songsdownload import Songsdetails

songs = Songsdetails("query","location")

songs.downloadsongs("Your Query")
songs.downloadlyrics("Your Query")

```
<br />


``` python
from songsdownload import Songsdetails

listofsongs = ["song1","song2"]
downloadsongarray(listofsongs)

```
<br />

![Result](https://raw.githubusercontent.com/ashen8810/Flash/6c2d64da4613342ed9122317e97142938230c7da/image.png?token=ARQPXPO5Z6VYOCMWRFWUEHTALXW54)


## License

© 2021 Ashen Ranaweera

This repository is licensed under the MIT license. See LICENSE for details.
