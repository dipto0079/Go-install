## Go install
<hr/>
<h4 align="left">
<a>https://go.dev/doc/install </a>
</h4>

<h4 align="left">
sudo rm -rf /usr/local/go && sudo tar -C /usr/local -xzf Downloads/go1.17.3.linux-amd64.tar.gz
</h4>

<h4 align="left">
mkdir -p go/{src,bin,pkg}
</h4>

## Protoc install
<hr/>
<h4 align="left">
<a>https://grpc.io/docs/protoc-installation</a>
</h4>
<h4 align="left">
sudo apt install -y protobuf-compiler
</h4>
<h4 align="left">
protoc --version
</h4>
<h4 align="left">
go get -u github.com/golang/protobuf/{proto,protoc-gen-go}
</h4>
<h4 align="left">
export GO_PATH=~/go
</h4>
<h4 align="left">
export PATH=$PATH:/$GO_PATH/bin
</h4>

 
