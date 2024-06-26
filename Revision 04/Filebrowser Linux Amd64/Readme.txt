Command to build using Windows:
$env:GOOS = "linux"
$env:GOARCH = "amd64"
go build -o myproject