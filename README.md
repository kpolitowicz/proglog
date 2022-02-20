# proglog

## Manually intalled assets

Chapter 2:

wget https://github.com/protocolbuffers/protobuf/releases/download/v3.9.0/protoc-3.9.0-linux-x86_64.zip
sudo unzip protoc-3.9.0-linux-x86_64.zip -d /usr/local/protobuf
echo 'export PATH="$PATH:/usr/local/protobuf/bin"' >> ~/.zshrc
source ~/.zshrc
rm protoc-3.9.0-linux-x86_64.zip

go get google.golang.org/protobuf/...@v1.25.0

