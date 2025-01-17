# Inferno Ports

This repository contains GitHub workflows for ports of the
[Inferno operating system](https://inferno-os.org) to various hardware
platforms.

## Structure

Each build is defined in a workflow file that describes the process of
cloning the appropriate repository, obtaining dependencies and building the
port.

Generally, the name of each workflow file reflects the branch name in the
repository associated with that build. The exception to this being the
hosted i386 build.

## Builds and rebuilding

When browsing the repository on GitHub, you can select the Actions tab on the
repository page to see recent builds.

## Ports

When enabled, builds are performed for the following ports:

* STM32F405
* SAMD51
* Apollo3
* Teensy 4.1
* Raspberry Pi 1 or Raspberry Pi Zero (using [yshurik's port](https://github.com/yshurik/inferno-rpi))
* Raspberry Pi Pico (using [Caerwyn's port](https://github.com/caerwynj/inferno-os/tree/pico))
* Pimoroni Pico Plus 2

There is also a build for the hosted i386 version of Inferno.

See the [latest information](https://dboddie.github.io/inferno-ports) for a
list of the ports that are built using workflows.
