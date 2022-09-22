# GoLearning
Config files for my GitHub profile.
1. Key Features
-Simplicity
-Fast compile times
-Garbage collected
-Buit-in concurrency
-Compile to standalone binaries
2. Resources
-golang.org, golang.org/doc/, golang.org/pkg/, golang.org/project/, golang.org/help/
-play.golang.org
3. Setting up local Development
-Download and install the golang installer as per the details at https://go.dev/doc/install
-setting up environment: edit the .bashrc script, add export GOROOT=/usr/local/go
export PATH=$PATH:$GOROOT/bin, export GOPATH=/root/Documents/GoLang, export PATH=$PATH:$GOPATH/bin and save the file. source the updated .bashrc file with source command.
Run the go version to command to confirm the go installed properly which will output the go version. go env -w GO111MODULE=auto to enable the go get command.
