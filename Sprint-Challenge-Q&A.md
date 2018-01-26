# Sprint-Challenge--Computer-Architecture

## Binary, Decimal, and Hex

Complete the following problems:

* Convert `11001111` binary

    to hex: CF

    to decimal: 207


* Convert `4C` hex

    to binary: 1001100

    to decimal: 76


* Convert `68` decimal

    to binary: 1000100

    to hex: 44


## Architecture

One paragraph-ish:

* Explain how the CPU provides concurrency: 

Concurrent processing is a computing model in which multiple processors execute instructions simultaneously for better performance. Concurrent means something that happens at the same time as something else. Tasks are broken down into subtasks that are then assigned to separate processors to perform simultaneously, instead of sequentially as they would have to be carried out by a single processor. Concurrent processing is sometimes said to be synonymous with parallel processing.

* Describe assembly language and machine language:

An assembly language or assembler, often abbreviated asm, is a low-level programming language for a computer, or other programmable device, in which there is a very strong correspondence between the language and the architecture's machine code instructions. Each assembly language is specific to a particular computer architecture. In contrast, most high-level programming languages are generally portable across multiple architectures but require interpreting or compiling. Assembly language may also be called symbolic machine code.
Machine code or machine language is a set of instructions executed directly by a computer's central processing unit (CPU). Each instruction performs a very specific task, such as a load, a jump, or an ALU operation on a unit of data in a CPU register or memory. Every program directly executed by a CPU is made up of a series of such instructions. The phrase 'directly executed' needs some qualification: machine code is by definition the lowest level of programming detail visible to the programmer, but internally many processors use microcode or optimise and transform machine code instructions into sequences of micro-ops in a sophisticated way.

* Suggest the role that graphics cards play in machine learning:

Efficient machine learning alogrithms are highly dependent on the raw speed of mathematical operations. For decades, we thought that neural network algorithms did not work well because of all sorts of complex problems, mainly related to an obscure mathematical issue named local optima in gradient descent. Machine learning involves always the same basic mathematical operations and GPUs are perfectly capable of handling this. Machine learning requires those operations to be processed in parallel on massive amounts of data. In fact, it is much more efficient to do 2 million tasks in one shot on a slow GPU, than it is do them sequentially on an extremely fast CPU. 