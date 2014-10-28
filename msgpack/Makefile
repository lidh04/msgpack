.PHONY:  all clean

all: msgpack-decode

msgpack-decode: msgpack-util.lisp
	@mkdir -p bin
	buildapp --output bin/$@ --load $^ --entry main


clean:
	@rm -f bin/*
	@echo "clean success"
