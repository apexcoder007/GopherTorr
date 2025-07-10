# GopherTorr


Tiny BitTorrent client written in Go.

## Install

```sh
go get github.com/apexcoder007/GopherTorr
```

## Usage
Try downloading Debian!

```sh
go run main.go debian-12.11.0-amd64-netinst.iso.torrent debian.iso 
```


## Limitations
* Only supports `.torrent` files (no magnet links)
* Only supports HTTP trackers
* Does not support multi-file torrents
* Strictly leeches (does not support uploading pieces)