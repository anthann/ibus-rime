# ibus-rime

Rime Input Method Engine for Linux/IBus

project home: [rime.im](https://rime.im)

code repository: https://github.com/rime/ibus-rime

license: GPLv3-or-later

## installation

Refer to https://github.com/rime/home/wiki/RimeWithIBus

build dependencies:

  - pkg-config
  - cmake>=2.8
  - librime>=1.0 (development package)
  - libibus-1.0 (development package)
  - libnotify (development package)
  - plum (submodule)

runtime dependencies:

  - ibus
  - librime>=1.0
  - libibus-1.0
  - libnotify
  - rime-data (provided by plum)

## compile on ubuntu 18.04

1. Install dependencies: 

```
apt install libboost-all-dev libgtest-dev libyaml-cpp-dev libleveldb-dev libmarisa-dev libopencc-dev libibus-1.0-dev libnotify-dev
```

2. Fix gtest issue:

[gtest](https://github.com/AppImage/AppImageKit/issues/571#issuecomment-349471627)

3. install:

```
./install.sh
```
