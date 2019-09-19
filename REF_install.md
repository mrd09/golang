https://tecadmin.net/install-go-on-ubuntu/

```
wget https://dl.google.com/go/go1.12.7.linux-amd64.tar.gz

sudo tar -xvf go1.12.7.linux-amd64.tar.gz
sudo mv go /bin

export GOROOT=/usr/local/go
export PATH=$GOROOT/bin:$PATH

go version
```