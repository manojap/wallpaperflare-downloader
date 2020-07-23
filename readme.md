# wallspyder

Set of wallpaper download automation scripts using selenium package. You can serach and download wall paper in a single line of brilliant python code,
using the appropriate class and methods.

# Websites Included

There are plenty of website which make available awesome wallpapers , but only following websites are available

1. http://wallpaperflare.com

# How to use 

```
git clone https://github.com/manojap/wallspyder.git

pip install -r  requirements.txt

from wallspyder import flareDownloader

code=flareDownloader('python').download(30)
```

# Default Save location 

make sure your save location is set to `default [Firefox]` or do it for the `first time`.

# Delay

`Use delay` for wait some time for loading downloading button in slower internet connection

```
cars = flareDownloader('cars').download(delay=100)
```

Even though I included the Firefox and chrome support , only Firefox make good result for me. So I recomment Firefox 

# Future 

More site will be included in the upcoming. Welcome to join me on this humble effort****