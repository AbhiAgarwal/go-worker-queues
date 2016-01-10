# go-worker-queues

Simple worker queues in Golang (following [this](http://nesv.github.io/golang/2014/02/25/worker-queues-in-go.html) tutorial).

Starting it just run `make` then to run with X workers do `./queued -n X`. To run tests just run `sh test.sh` then you should start seeing the incoming tasks, and the execution of the tasks.
