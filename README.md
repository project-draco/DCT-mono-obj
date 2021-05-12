# DCT-mono-obj
Draco Clustering Tool - Mono Objective algorithms

## Input
Module Dependency Graph (MDG) from standard input

## Output
clustered graph in DOT format on standard output.

## Running
```$ go mod init lns```

```$ go get -u github.com/exascience/pargo/parallel```

```$ go build```

```$ ./lns < software.mdg > software.dot```
