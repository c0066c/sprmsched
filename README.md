# sprmsched

This is used to demonstrate how to create two tasks for uniprocessor.

The execution time of each task is realized by using rtems_counter_delay_ticks(t0),
where t0 = rtems_counter_nanoseconds_to_ticks( 1000000 ); //counter: 1 tick is 1 ms.
