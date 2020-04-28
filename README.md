
## Docker run

```
$ cd compilerbook/9cc
$ docker run --rm -it -v $(pwd):/9cc compilerbook
user@2e4e9eb3950f:~$ cd /9cc
user@2e4e9eb3950f:/9cc$ ls
9cc  9cc.c  tmp.s
```

## Build by make

```
# only first
compilerbook/9cc$ make

compilerbook/9cc$ make test

# delete temp files
compilerbook/9cc$ make clean
```
