all:
	g++ *.c -lm
clean:
	rm -f a.out
run:
	./a.out
rerun:
	make clean
	make all
	make run
gimmeimage:
	make clean
	make all
	make run
	gnuplot gnuskrypt.sh
