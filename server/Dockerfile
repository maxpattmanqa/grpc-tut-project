From golang 

ENV GO111MODULE=on
ADD . /go/src/github.com/maxpa_qzrio/grpc-tut-project/server
Run go install github.com/maxpa_qzrio/grpc-tut-project/server
ENTRYPOINT ["/go/bin/server"]
EXPOSE 5300