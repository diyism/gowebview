# goAndView
go install gioui.org/cmd/gogio
go get github.com/diyism/goAndView
cd $GOPATH/src/github.com/diyism/goAndView/apps/hello
go mod tidy
gogio --target android ./
adb install hello.apk
