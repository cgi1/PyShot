# PyShot
A quick and easy to use handler around selenium/chromedriver to handle batch processing of input urls.

# Installation

## Pre-Req

Make sure to have the correct [chromedriver](https://sites.google.com/a/chromium.org/chromedriver/downloads). Correct means, it **must be** the same version as the installed Chrome on your machine/server. In Ubuntu you can check your version using 
```
$ sudo apt-get upgrade google-chrome-stable
google-chrome-stable ist schon die neueste Version (83.0.4103.97-1).
```

So you need to download the correct version from [here](https://sites.google.com/a/chromium.org/chromedriver/downloads) and than go like this:

```
wget https://chromedriver.storage.googleapis.com/83.0.4103.39/chromedriver_linux64.zip
unzip chromedriver_linux64.zip
sudo mv chromedriver /usr/bin/chromedriver 
```

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




