build:
	docker run -v `pwd`/:/build -w /build -u root tinygo/tinygo:0.39.0 tinygo build -o /build/hello.wasm -target wasi /build/main.go
