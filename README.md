
# XMR-Stak - Monero/Aeon All-in-One Mining Software

**XMR-Stak is ready for the POW change of Monero-v7, Aeon-v7 and Sumukoin-v3**

XMR-Stak is a universal Stratum pool miner. This miner supports CPUs, AMD and NVIDIA gpus and can be used to mine the crypto currency Monero and Aeon.

## HTML reports

## Video setup guide on Windows

[<img src="https://gist.githubusercontent.com/fireice-uk/3621b179d56f57a8ead6303d8e415cf6/raw/f572faba67cc9418116f3c1dfd7783baf52182ce/vidguidetmb.jpg">](https://youtu.be/YNMa8NplWus)
###### Video by Crypto Sewer

## Overview
* [Features](#features)
* [Supported altcoins](#supported-altcoins)
* [Download](#download)
* [Usage](doc/usage.md)
* [HowTo Compile](doc/compile.md)
* [FAQ](doc/FAQ.md)


## Features

- support all common backends (CPU/x86, AMD-GPU and NVIDIA-GPU)
- support all common OS (Linux, Windows and macOS)
- supports algorithm cryptonight for Monero (XMR) and cryptonight-light (AEON)
- easy to use
  - guided start (no need to edit a config file for the first start)
  - auto configuration for each backend
- open source software (GPLv3)
- TLS support
- [HTML statistics](doc/usage.md#html-and-json-api-report-configuraton)
- [JSON API for monitoring](doc/usage.md#html-and-json-api-report-configuraton)

## Supported altcoins

Besides [Monero](https://getmonero.org), following coins can be mined using this miner:

- [Aeon](http://www.aeon.cash)
- [Edollar](https://edollar.cash)
- [Electroneum](https://electroneum.com)
- [Graft](https://www.graft.network)
- [Intense](https://intensecoin.com)
- [Karbo](https://karbo.io)
- [Sumokoin](https://www.sumokoin.org)

If your prefered coin is not listed, you can chose one of the following algorithms:

- Cryptonight - 2 MiB scratchpad memory
- Cryptonight-light - 1 MiB scratchpad memory

Please note, this list is not complete, and is not an endorsement.


## Default Developer Donation

By default the miner will donate 2% of the hashpower (2 minute in 100 minutes) to my pool. If you want to change that, edit [donate-level.hpp](xmrstak/donate-level.hpp) before you build the binaries.

