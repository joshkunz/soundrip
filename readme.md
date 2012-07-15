soundrip
=========

It's pretty simple actually, just rips music from soundcloud because
sometimes they feel like removing the download button.

```
$ soundrip --help
usage: soundrip [-h] [-g] url [url ...]

positional arguments:
  url                   URL of the page of the song you want to download

optional arguments:
  -h, --help            show this help message and exit
  -g, --greedy, --page  Download all detected tracks on a page. This is useful
                        if you want to download an entire page of tracks.
```

# -g flag

On track pages it downloads the track plus any additonal 'reccomended' tracks.
On artist pages it will basicall download any tracks you see. But best of all,
on 'set' pages it will download the entire set (basically an album)

# Installation

Just make sure the packages in requirements.txt are fulfilled.
`pip install -r requirements.txt` and that the soundrip script is
somewhere in your path.

Enjoy.
