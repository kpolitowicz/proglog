# proglog

## Manually intalled assets

Chapter 2:

wget https://github.com/protocolbuffers/protobuf/releases/download/v3.9.0/protoc-3.9.0-linux-x86_64.zip
sudo unzip protoc-3.9.0-linux-x86_64.zip -d /usr/local/protobuf
echo 'export PATH="$PATH:/usr/local/protobuf/bin"' >> ~/.zshrc
source ~/.zshrc
rm protoc-3.9.0-linux-x86_64.zip

go get google.golang.org/protobuf/...@v1.25.0

Chapter 3:

go get google.golang.org/grpc@v1.32.0
go get google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.0.0

Chapter 5:

go get github.com/cloudflare/cfssl/cmd/cfssl@v1.4.1
go get github.com/cloudflare/cfssl/cmd/cfssljson@v1.4.1

go get github.com/casbin/casbin@v1.9.1

Chapter 6:

go get go.uber.org/zap@v1.10.0
go get go.opencensus.io@v0.22.2
