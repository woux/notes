k1: 
1. context switch in and out of kernel
2. collection of task descriptors
3. request mechanism for providing arguments and returning results
4. priority queues for scheduling
5. kernel algorithms for manipulating task descriptors and priority queues

Kernel primitives: 

`int Create (int priority, void (*code))`

`int MyTid()`

`int MyParentTid()`

`void Pass()`

`void Exit()`

User Tasks

1. First user task
    * create two test tasks at lower priority
    * create two test tasks at higher priority
    * lower priority tasks created before higher priority tasks
    * first user task call Exit

2. Oher Tasks