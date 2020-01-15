# News-Crawler

A News Crawler which will extract articles from URL links of newspaper websites.

This crawler is specifically developed to download news articles pertaining to the following categories: **Politics,Technology,Sports,Business,World,Entertainment**

## Pre-requisites:

The crawler uses python's **[newspaper3k library](https://newspaper.readthedocs.io/en/latest/)**

**Installation
If you are on Debian / Ubuntu, install using the following:**

Install pip3 command needed to install newspaper3k package:
> $ sudo apt-get install python3-pip</br>

Python development version, needed for Python.h:
> $ sudo apt-get install python-dev

lxml requirements:
> $ sudo apt-get install libxml2-dev libxslt-dev

For PIL to recognize .jpg images:
> $ sudo apt-get install libjpeg-dev zlib1g-dev libpng12-dev
NOTE: If you find problem installing libpng12-dev, try installing libpng-dev.

**Install the distribution via pip **
> $ pip3 install newspaper3k

**If you are on OSX, install using the following, you may use both homebrew or macports: **

> $ brew install libxml2 libxslt

> $ brew install libtiff libjpeg webp little-cms2

> $ pip3 install newspaper3k
