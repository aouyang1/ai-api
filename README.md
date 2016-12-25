# ai-api

Setting up Go dev environment

1. Set GOPATH to top repository level e.g. GOPATH=/home/ai-api
2. Set GOBIN to $GOPATH/bin (Make bin directory if not exist)
3. If github.com/gorilla/mux is not in the src directory go to $GOPATH/src/aouyang1/ai-api and run `go get`
4. Move to $GOPATH/src/github.com/aouyang1/ai-api
4. Run the API server by running `go run <all go files>`
5. You can build the binary version of the API server by running `go install`
6. Find the `ai-api` binary under $GOPATH/bin and run `./ai-api`
7. Checkout the following endpoints

* localhost:8080
* localhost:8080/todos
* localhost:8080/todos/somethin

