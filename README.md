# GPT example
|  Linux | Windows| ESP32 | MSP432 |
|:--|:--|:--|:--|
|:heavy_check_mark:|:heavy_check_mark:|:x:|:x:|
## Introduction
Go [here](https://github.com/SimulationEverywhere/cadmium_v2/wiki/5.-Examples-of-DEVS-Models) for a detailed explanation of the GPT model

## Dependencies
This project assumes that you have Cadmium installed in a location accessible by the environment variable $CADMIUM.
_Note: Ignore this if you are using the server; all the dependencies are pre-installed_

## Build
To build this project, run:
```sh
source build_sim.sh
```
__NOTE__: Everytime you run build.sh, the contents of `build/` and `bin/` will be replaced.

## Execute
To run the project, run:
```sh
./bin/GPT_Example <Period of job creation> <time taken to process> <total observation time>
```
Replace everything within `<...>`. And example:
```sh
./bin/GPT_Example 3 2 10
```
