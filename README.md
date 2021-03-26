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

songs = Songsdetails("query","location") #default location is cwd

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

![](/image.png)
## License

© 2021 Ashen Ranaweera

This repository is licensed under the MIT license. See LICENSE for details.
