

[Java Threading Threadstates](Java_Threading_Threadstates.png)


### Number of Threads

Without any limitations, increasing the number of threads could


In practice, however, the number of threads executing in parallel
is limited by the CPU. The number of active threads should equal
the number of cores in the CPU and, depending on your application,
can be increased by a factor of two or four. Adding more active
threads will probably have a negative effect.

[Java Threading Threadcount](Java_Threading_Threadcount.png)

> As a part of a software test for a customer, i wrote a lot
> of data to the application. The programmer started a new
> thread for every block of data in the hope that the
> computer was fast enough to process each block.
>
> With a large amount of data, the application went slower
> to process the input. It went worse while more data was
> arriving at a constant pace. It took less than 30 minutes
> an the application broke down because too many threads
> were fighting for the CPU  

