# torrent-client



## Install

```sh
go get github.com/veggiedefender/torrent-client
```

## Usage
Try downloading [Debian](https://cdimage.debian.org/debian-cd/current/amd64/bt-cd/#indexlist)!

```sh
torrent-client debian-10.2.0-amd64-netinst.iso.torrent debian.iso
```

[![asciicast](https://asciinema.org/a/xqRSB0Jec8RN91Zt89rbb9PcL.svg)](https://asciinema.org/a/xqRSB0Jec8RN91Zt89rbb9PcL)


## Limitations
* Only supports `.torrent` files (no magnet links)
* Only supports HTTP trackers
* Does not support multi-file torrents
* Strictly leeches (does not support uploading pieces)
