# DS-seminar
Distribited System Seminar

how to run parallel_sobel.c

gcc -o p_filter -O3 -fopenmp parallel_sobel.c

./p_filter

how to sun sobel.c

gcc -o filter -O3 -fopenmp sobel.c

./filter


References:

https://people.sc.fsu.edu/~jburkardt/c_src/pgma_io/pgma_io.html

https://www.researchgate.net/publication/239398674_An_Isotropic_3_3_Image_Gradient_Operator

http://on-demand.gputechconf.com/gtc/2016/presentation/s6510-jeff-larkin-targeting-gpus-openmp.pdf

