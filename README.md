### goreplay
---
https://github.com/buger/goreplay

```
make build
make test
docker run -v `pwd`:/go/src/github.com/buger/gor/ -p 0.0.0.0:8000:8000 -t -i gor:go go test ./. -run TestEmitterFiltered -timeout 60s
-ldflags "-X main.VERSION=DEV-1482398347 -extldflags \"-static\"" -v
```

```go
while read line; do
  echo $line
end
```

```
```


