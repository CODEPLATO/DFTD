Doorbell for the Deaf (DFTD)
====

## Introduction/Sypnosis
Microcontroller code behind the creation of a vibration doorbell for the deaf.

## Sharing of code on GITHUB

We chose GITHUB as a platform for storing our code instead of dropbox for the following reasons:

1. 
2. Documentation for our code
3. Multiple persons can work on the same code (but preferably not unless you’re already familiar with git) at the same time.
        working on separate documents (different folders different code) in parellel is readily supported


## Prerequisites

1. [Commandline IDE](http://inotool.org/) for uploading code into the arduino board. (See [quick tutorial](http://inotool.org/quickstart))
 * Reason for chosing a command line (terminal) ide instead of the GUI is it allows easy integration into scripts eg. python/perl/bash
2. picocom (serial monitor)
3. Python (Anaconda Distribution)

### Installation of prerequisites

| Software | Tutorial                                                                                                            |
| ----     | ----                                                                                                                |
| INO:     | [Installation](http://codeslingers.co.uk/2014/04/19/developing-arduino-in-vim/)                                     |
| picocom: | [Homebrew](http://brew.sh/) brew install picocom                                                                    |
| iterm    | Terminal replacement for OSX                                                                                        |
| python   | using [pyenv](https://github.com/yyuu/pyenv) use the anaconda distribution, comes with various scientific libraries |


## Arduino

### Sensors

[MySensors nRF24L01](https://github.com/mysensors/Arduino/tree/master/libraries/MySensors)
see [here](http://www.mysensors.org/about/components) for the components

## Misc. 

* passwordless login using `ssh-keygen`
* pass github your `.ssh/id.rsa.pub` to github to clone securely.
* BASH ALIASES for shorterning commands like ssh user@xxx.xxx.xxx.xxx 
