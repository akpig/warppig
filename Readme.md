# Warp Pig

## platform code
[https://github.com/akpig/warppig/releases](https://github.com/akpig/warppig/releases)

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


## docker
1. docker
    ```
    docker run --rm -it -v $(pwd)/warppig_config:/config -p 3000:3000 -p 3001:3001 akpig/warppig
    ```
2. docker-compose
    - download
    ```
    curl -L https://raw.githubusercontent.com/akpig/warppig/main/docker/docker-compose.yaml -o docker-compose.yaml
    ```
    - run
    ```
    docker-compose up -d
    ```
