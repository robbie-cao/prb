# prb

Persistent Ring Buffer

## Objective

- Fixed-size (selectable at run-time when creating it, not compile-time) circular buffer
- Can hold objects of any type
- Multi-tasking embedded environment
- Persistence
- Operations:
  * put at the tail
  * get from the head
  * return the count
  * delete a buffer


## Reference

- https://en.wikipedia.org/wiki/Circular_buffer
- https://github.com/pthrasher/c-generic-ring-buffer
- https://github.com/dhess/c-ringbuf
- https://github.com/cloudyourcar/ringfs
- https://github.com/xant/libhl
- https://gist.github.com/CAFxX/571a1558db9a7b393579
- http://www.boost.org/doc/libs/1_48_0/libs/circular_buffer/doc/circular_buffer.html
- https://github.com/angrave/SystemProgramming/wiki/Synchronization,-Part-8:-Ring-Buffer-Example
