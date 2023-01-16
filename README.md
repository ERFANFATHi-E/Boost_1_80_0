# boost_1_80_0

[![CircleCI](https://circleci.com/gh/rcsoccersim/rcssserver/tree/master.svg?style=svg)](https://circleci.com/gh/rcsoccersim/rcssserver/tree/master)
![License](https://img.shields.io/github/license/rcsoccersim/rcssserver.svg)

![boost](https://user-images.githubusercontent.com/120306894/212659163-c586affb-ec30-4351-8495-55766f7897cb.png)

boost file &amp; how to install 
-----------------------

- Boost 1.38 or later https://www.boost.org/

You may need install some pkgs :

```
sudo apt-get update
sudo apt-get install build-essential g++ python-dev autotools-dev libicu-dev libbz2-dev libboost-all-dev
```

Secondly there are some few steps to do :

```
./bootstrap.sh --prefix=/usr/
./b2
sudo ./b2 install
```

TADAAA! DONE.
If there is any problem you can contact us via fathye897@gmail.com
------------------------
