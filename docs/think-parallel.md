## Think Parallel

Think whether the problem can be parallelized. Then decide on your algorithm and design. Not the other way around

TBB allows tailoring Task-based Parallelism and Data-level Parallelism together.

If we scale a program beyond its peak-performance limit, the overhead for distributing and synchronizing dominate.


Acquiring a lock and then invoking a function or subroutine that happens to use locks is often the source of multiple lock issues.


### 4 Design Spaces

1. Finding Concurrency
2. Algorithm Structures
3. Supporting Structures
4. Implementation Mechanisms


### Grain Size
The number of iterations need to done on a single processor. Grain size helps to hide out parallel overhead. Larger the Grain Size, better the performance. Don't think of it as the number of iterations that can be done on a processor. Think of it as how many number of iterations are enough to keep the overhead minimum.
