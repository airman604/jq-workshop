# JSON parsing with jq

Welcome to **JSON parsing with jq**, a practical workshop put together by @Defcon604 crew. To get the most out of it, please come prepared.

## Pre-requisites
* Install `jq` (instructions below)
* Download and unzip [the dataset](https://www.secrepo.com/honeypot/honeypot.json.zip)

## Installing **jq** in Linux
Chances are `jq` is already installed, check using `which jq`. If not, you can install it using one of these, depending on your Linux disto:
* `sudo apt install jq`
* `sudo dnf install jq`

## Installing **jq** in Mac OS
Easiest way to install `jq` on Mac OS is through Homebrew.
* If you don't have Homebrew yet, install by following the instructions here: https://brew.sh/
* Install `jq` with `brew install jq`

Alternative instructions (not tested!): https://stedolan.github.io/jq/download/

## Windows
We do not recommend using Windows for this workshop, and none of the labs have been tested with Windows. Here's a couple thoughts if that's your only option:
* Use a Linux virtual machine and follow Linux instructions
* Use WSL (Windows Subsystem for Linux) on Windows 10. Check the istructions here: https://docs.microsoft.com/en-us/windows/wsl/install-win10

_None of Windows options have been tested_

# Additional Resources
You can find [slides](JSON%20parsing%20with%20jq%20%28no%20lab%20answers%29.pdf) in this repository, this is the version that doesn't have lab answers, full version will be available after the workshop.

[Dataset data structure cheatsheet](dataset_structure_cheatsheet.md) - we explore the structure of the dataset in the labs, this is useful as a reference.