# Warp Pig

## communication and interaction channels
- telegram channel: [@warppig](https://t.me/warppig)
- telegram group: [@warppig1](https://t.me/warppig1)


## What is Warp Pig?
Warp Pig is a custom proxy tool for exporting the Cloudflare Warp network to SOCKS5 or HTTP protocols.

## Features
- Automatically select the fastest warp node.
- Access via socks5 protocol
- Access via http protocol
- Automatically obtain Warp key

## How to use it?
1. Download the binary for your platform
2. Run it
    ```
    ./warp-pig
    ```
    Note: In the absence of a configuration file, a default configuration file named "config.yaml" will be automatically generated in the work directory.

## More usage
1. Specify configuration file
    ```
    ./warp-pig -c ./config.yaml
    ```
2. Specify cache directory
    ```
    ./warp-pig --cache ./cache
    ```
    Cache directory is used to cache running info for next running



