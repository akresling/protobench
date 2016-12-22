# Go Benchmark : JSON v. Protobuf

This small benchmark is done to test the differences in size and speed between 
json and protobuf.

### Get the code and try it yourself

``` go get github.com/akresling/protobench ```

To run the benchmark:
```
go test --bench=.
```

Try changing the content of the data structure in proto_test.go and see the results

### Libraries used:
JSON library :
``` 
encoding/json 
```

Protobuf library : 
``` 
github.com/golang/protobuf/proto
```
