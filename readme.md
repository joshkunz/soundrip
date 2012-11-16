soundrip
=========

It's pretty simple actually, just rips music from soundcloud because
sometimes they feel like removing the download button.

```bash
$ soundrip --help
usage: soundrip [-h] [-d] url [url ...]

positional arguments:
  url         URL of the page of the song you want to download

optional arguments:
  -h, --help  show this help message and exit
  -d, --dir   Make a directory to hold all of the new files in
```

# Automatic url handling

You can feed soundrip a url to any page and it will try and 'do the right thing'.
For example you can give it the url to an artist page, and it will download all of
that artist's tracks. Or you can give it a url to a 'set' and it will download 
all of the tracks in the set automatically.

You can use this in conjuntion with the `--dir` parameter to have soundrip automatically
create folder to hold all of the tracks downloaded from an artist page or set.

# Installation

Just make sure the packages in requirements.txt are fulfilled.
`pip install -r requirements.txt` and that the soundrip script is
somewhere in your path.

Enjoy.
