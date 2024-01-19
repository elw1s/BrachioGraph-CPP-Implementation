# BrachioGraph C++ Library

## Overview

This project includes the C++ implementation of the BrachioGraph library developed by [Daniele Procida](https://github.com/evildmp/BrachioGraph) which is written in Python.

To view the project utilizing this library, click [here]([https://github.com/evildmp/BrachioGraph](https://github.com/elw1s/2DOF-Painter-Robot-Arm)).

## Installation

Install OpenCV for c++ through [GeeksForGeeks](https://www.geeksforgeeks.org/how-to-install-opencv-in-c-on-linux/)

Then install
```bash
  sudo apt update
  sudo apt install nlohmann-json3-dev
  sudo apt install xtensor-dev
  sudo apt-get install libopencv-dev
  wget https://github.com/joan2937/pigpio/archive/master.zip
  unzip master.zip
  cd pigpio-master
  make
  sudo make install
```

Run
```bash
  mkdir build & cd build
  cmake ..
  make
  ./brachioGraph
```
