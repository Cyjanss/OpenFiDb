# OpenFiDb
Collaborative Function ID datasets plugin for Ghidra

## How does it works ?

The `OpenFiDb` plugin allows every user to easily get a large dataset of `.fidb` files. These are used by the plugin `FunctionID` of Ghidra in order to recognize well known functions signatures based on their binary format.

Once a researcher identified a function in Ghidra, he can share it thanks to the `OpenFiDb` plugin and it will increase the collaborative dataset.

This plugin uses the repository of threatrack : https://github.com/threatrack/ghidra-fidb-repo as the base of `.fidb` files. For more information about how it was generated and about which librairies are included, please see the [README](ghidra-fidb-repo/README.md) of this fork.

Collaborative Function ID datasets are in the folder [Collaborative](Collaborative/). Each user has a unique id and a unique `.fidb` file to allow other users to choose which one they wants to use. 

To prevent dupplicates hashes of functions, a big file contains all functions ever pushed by the `OpenFiDb` plugin and is in the file `OpenFiDb.fidb` in the root folder.

## Installation

In construction...

## Usage

## Contributing

## License