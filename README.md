# GoHelloWorld
Tip: Replace myusername with dockerhub username
// Clone
```
git clone https://github.com/atulkamble/GoHelloWorld.git
cd GoHelloWorld
```

Containerise Go Hello World App
// Goto Official Golang | Download | Install https://go.dev/
```
go version
go help
```
// (Optional)
```
cd D:/Project
mkdir goproject
cd .\goproject\
```
```
New-Item main.go
code main.go
OR
notepad main.go
```
// Add following code to main.gopackage main
```
import "fmt"

func main() {
    fmt.Println("Hello World!")
}
```
// initilization
```
go mod init v1
go mod tidy
```
// build app
```
go build -o main
```
// run app
```
go run main.go
```
// building image
```
docker build -t atuljkamble/gohelloworld .
```
// listing image
```
docker images
```
// run docker image
```
docker run atuljkamble/gohelloworld
```

// Push Image to docker hub
```
docker push atuljkamble/gohelloworld
```
