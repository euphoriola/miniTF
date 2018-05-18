
out_dir:
	$(shell \
	if [ ! -d "out/" ]; then \
	  mkdir out/; \
	fi;)

all: out_dir
	gcc -c arithmetic.c -o out/arithmetic.o
	ar rc out/libarithmetic.a out/arithmetic.o

clean:
	rm -rf out/
