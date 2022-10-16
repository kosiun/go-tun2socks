#Build with OpenWRT 24_KC 

GOOS=linux GOARCH=mips GOMIPS=softfloat go build -ldflags '-s -w -X main.version=v1.16.11-2-g301549c' -o tun2socks -v -tags 'socks'
