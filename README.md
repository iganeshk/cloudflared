<h1 align="center">
  <a href="https://github.com/iganeshk/cloudflared/" title="Argo Tunnel client x64 precompiled binary">
    <img alt="Argo Tunnel client x64 precompiled binary" src="https://github.com/iganeshk/cloudflared/raw/master/argo.png" width="40%"/>
  </a>
  <br />
  Argo Tunnel client arm64 precompiled binary
</h1>

Contains the command-line client and its libraries for Argo Tunnel, a tunneling daemon that proxies any local webserver through the Cloudflare network.

## GO Installation

```
wget https://dl.google.com/go/go1.11.5.linux-arm64.tar.gz
tar -xvf go1.11.5.linux-arm64.tar.gz
sudo mv go /usr/local
export GOROOT=/usr/local/go
export GOROOT=/usr/local/go
mkdir /home/user/.gopath
export GOPATH=/home/user/.gopath
export PATH=$GOPATH/bin:$GOROOT/bin:$PATH
```

## Building for arm64 architecture

    go get -u github.com/cloudflare/cloudflared/cmd/cloudflared

User documentation for Argo Tunnel can be found at https://developers.cloudflare.com/argo-tunnel/
