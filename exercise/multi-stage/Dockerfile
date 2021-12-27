 golang:1.13

 /go/src/href-counter/

 vendor vendor
 app.go	.

 CGO_ENABLED=0 GOOS=linux go build -a -installsuffix cgo -o app .

 alpine:3.10
 apk --no-cache add ca-certificates

 /root/

 --from=0 /go/src/href-counter/app    .

 ["./app"]
