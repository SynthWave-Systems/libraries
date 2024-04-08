# ![](../../assets/zstd.png) Zstandard x64

Zstandard static libraries compiled for x64 uasm assembler 

Zstandard: https://facebook.github.io/zstd/ https://github.com/facebook/zstd

> Zstandard is a real-time compression algorithm, providing high compression ratios.

## Usage

* Copy `zstd_x64.inc` to your `uasm\include` folder (or wherever your includes are located)

* Copy `zstd_x64.lib` to your `uasm\lib\x64` folder (or wherever your 64bit libraries are located)

* Add the following to your project:
  
  ```assembly
  include zstd_x64.inc
  includelib zstd_x64.lib
  ```

**Note:** `zstd_x64.lib` also requires the Windows C Universal Runtime

## Functions

Zstandard Library reference documentation is available on the Zstandard website: [http://facebook.github.io/zstd/zstd_manual.html](http://facebook.github.io/zstd/zstd_manual.html)

## Download

The latest downloadable release is available [here](https://github.com/mrfearless/libraries/blob/master/releases/Zstd_x64.zip?raw=true)