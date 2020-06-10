# PyShot
A well-featured handler around selenium/chromedriver to handle batch processing of input urls.

# Installation

## Pre-Req

Make sure to have

```
pip3 install selenium
```

## Using pip

Will be available later

## Install from repo

```
pip3 install git+https://github.com/cgi1/Pyshot/
```

# Get Started

The normal behaviour is, that `screenshots.py` is reading from an input file (`link_path`) which contains one url per line. It than works through that list and generating screenshots to `output_dir`. The screenshots are saved as `base64` encoded url to the `output_dir` to prevent problems with special characters in the original URL. 

# Development status

I started today writing a wrapper around these things and will develop it further when I need to adapt.




