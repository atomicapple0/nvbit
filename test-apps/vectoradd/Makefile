all:
	/usr/local/cuda-11/bin/nvcc -ccbin=$(CXX) -O3 -arch=sm_80 vectoradd.cu -o vectoradd

clean:
	rm -f vectoradd
