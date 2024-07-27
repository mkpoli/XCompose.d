# Compose configuration

This repository contains a custom compose key configuration that I use daily. It is meant to be used with [WinCompose](http://wincompose.info/), but should work with other compose key software that supports the xcompose format.

## Usage

1. Install [WinCompose](http://wincompose.info/).
2. Copy the all `.compose` files to a directory under your user profile. It is usually located in. `C:\Users\<username>\XCompose.d`.
3. In your custom configuration `C:\Users\<username>\.XCCompose`, add the following lines to the end of the file:
    ```xcompose
    include "XCompose.d/phonetic.compose"
    include "XCompose.d/unicode.compose"
    # add more files here
    ```