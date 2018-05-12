# koshort
![Build Status](https://travis-ci.org/koshort/koshort.svg?branch=master)
![Documentation Status](https://readthedocs.org/projects/koshort/badge/?version=latest)
![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)
[![PyPI version](https://badge.fury.io/py/koshort.svg)](https://badge.fury.io/py/koshort)

한국어 인터넷 트렌드 스트리밍과 처리를 위하여 만들어진 파이썬 패키지 코숏.  
koshort is a Python package for Korean internet trends streaming and processing... or maybe Korean domestic cat.

* English Documentation (In progress..): [http://koshort.readthedocs.io/](http://koshort.readthedocs.io/)
* 한국어 문서 (준비중..): [http://koshort.readthedocs.io/](http://koshort.readthedocs.io/)

## Installation
The easiest way to install the latest version is by using pip/easy_install to pull it from PyPI:

```bash
pip install koshort
```

You may also use Git to clone the repository from GitHub and install it manually:

```bash
git clone https://github.com/koshort/koshort.git
cd koshort
python setup.py install
```

Python 3.3, 3.4, 3.5 & 3.6 are supported.  
3.7 compatibility soon will be available.

## Examples
```shell
# Install koshort
git clone https://github.com/koshort/koshort.git
cd koshort

# Streaming with koshort.stream.naver
python
>>> from koshort.stream import naver
>>> streamer = naver.NaverStreamer()
>>> streamer.stream()
cj채용
온주완의 뮤직쇼
유상무
현대차
...
```

## Copyright
copyright by 2018 Nyanye with :purple_heart:
