# poc-rabbit

`Golang example`

```sh
$ go run topic/emit.go queue cagale
$  [x] Sent cagale
```

```sh
$ go run topic/receive.go queue
$  [x] cagale
```

```sh 
$ go run topic/receive.go queue
$  [x] cagale
```