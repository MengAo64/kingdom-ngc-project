# Discord Nitro Sniper

## Linux build

If you are on Windows you need to download WSL (google about it). Make sure you use an older Ubuntu version
so that you can run the compiled on newer versions of Ubuntu (or any other distribution whatever).

```sh
go build -ldflags "-s -w" -o isniper *.go && strip -s isniper
```
