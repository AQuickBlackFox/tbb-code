## Think Parallel

Think whether the problem can be parallelized. Then decide on your algorithm and design. Not the other way around

TBB allows tailoring Task-based Parallelism and Data-level Parallelism together.

If we scale a program beyond its peak-performance limit, the overhead for distributing and synchronizing dominate.


Acquiring a lock and then invoking a function or subroutine that happens to use locks is often the source of multiple lock issues.
