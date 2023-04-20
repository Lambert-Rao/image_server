# Share Shift

Other Language: [简体中文](./docs/zh-CN/README.zh-CN.md)

 <svg width="767" height="300" xmlns="http://www.w3.org/2000/svg">
 <g>
  <title>Layer 1</title>
  <text font-style="italic" transform="matrix(1.99102 0 0 1.99102 460.065 233.22)" stroke="#0d2270" xml:space="preserve" text-anchor="start" font-family="'Alegreya'" font-size="86" id="svg_1" y="-42.58992" x="-187.25809" fill="#1faaef">SHARE</text>
  <text stroke-width="0.3" stroke="#4e2160" font-style="italic" xml:space="preserve" text-anchor="start" font-family="'Brygada 1918'" font-size="86" id="svg_5" y="244" x="538" fill="#8b1cdb">shift</text>
  <rect id="svg_8" height="5" width="433" y="162" x="297.83333" stroke="#1faaef" fill="#a961d3"/>
 </g></svg>



[toc]

build a cloud share platform with fastdfs and nginx



## Install

first, you need to build the enviroment, see [the enviroment file](./docs/enviroment.md), then you can install the project as follow:

```bash
    # install
    mkdir build
    cd build
    cmake ..
    make
```

## Usage

```bash
    cd ShareShift
    cp share_shift.conf ShareShift/build
    tmux
    ./share_shift
```