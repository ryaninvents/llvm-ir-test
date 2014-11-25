# llvm-ir-test

Fooling around with the LLVM compiler. This simple example just
compiles the "hello world" program written in IR.

Requires [Docker](http://docker.io).

## Usage

```
docker pull baconscript/llc
docker run -it -v $(pwd):/root baconscript/llc /root/compile
./hello
```