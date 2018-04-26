* Tutorial:
- http://nesv.github.io/golang/2014/02/25/worker-queues-in-go.html
* Building:
- go build ./...
- ./go-worker-queues -n=2 -http=127.0.0.1:4242
* curl req:
- curl -X POST '127.0.0.1:4242/work?name=pinku&delay=5s'