# WizCoin


Moduł Pythona zawierający reprezentacje monet galeon, sierp i zwitek czarodziejskiej waluty.

## Installation

To install with pip on macOS or Linux, run:

    python3 -m pip install wizcoin

To install with pip on Windows, run:

    py -m pip install wizcoin

## Quickstart Guide

Here is some example code demonstrating ho wthis module is used:

    >>> import wizcoin
    >>> coin = wizcoin.WizCoin(2, 5, 10)
    >>> str(coin)
    '2g, 5s, 10k'
    >>> coin.value()
    1141

## Contribute

If you'd like to contribute to WizCoin, check out https://github.com/marek-szostak/wizcoin
