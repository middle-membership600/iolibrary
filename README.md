# CS 61 Class Project: Enhanced Synchronization for Reading and Writing Library

In this project, completed as a part of the CS 61 class, I have successfully implemented an advanced synchronization mechanism on a self-coded reading and writing library, which notably outperforms the standard `stdio` library. I acheived this through the strategic use of locking mechanisms and optimization techniques such as caching, seeking, and flushing.

## Features

### Superior Performance to `stdio`
By leveraging optimized synchronization techniques, our library manages to surpass the performance of the `stdio` library, enhancing both sequential and non-sequential read-write accesses.

### Fine-Grained vs Coarse-Grained Locking
Our library employs a dual locking strategy to facilitate safe multithreading, allowing users to choose between fine-grained and coarse-grained locking based on their specific requirements.

### Caching, Seeking, and Flushing
We have incorporated caching, seeking, and flushing functionalities to further optimize the performance of read-write operations, ensuring a smoother and faster execution compared to the `stdio` library.

## Extra Credit Phase 4: Integration with Pset 6 Functions

In the extra credit phase 4 of the project, I have successfully integrated the IO61 library developed in Pset 4 with the functions outlined in Pset 6, enhancing the library's capabilities and functionalities. The integrated functions include:

- `write`: A function to facilitate writing operations.
- `writec`: A function designed to write characters.
- `read`: A function to streamline reading operations.
- `readc`: A function to read characters.
- `open`: A function to open files and establish connections.
- `close`: A function to close files and terminate connections safely.
