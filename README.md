# OpenVGDB Sorter

A small utility for sorting legal dumps using the OpenVGDB database.



## Installation

1. Clone this repo.
2. Download the latest release of [OpenVGDB](https://github.com/OpenVGDB/OpenVGDB/releases) and place it in this folder.



## Usage

Move your dumps into a directory called `dumps`, and then run the following:

```bash
./vgdb-sorter --input=dumps --output=collection
```

All identified dumps will be renamed and placed in `collections/[system]/[region]`.
Anything that remains was unable to be identified.