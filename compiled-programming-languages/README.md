# Compiled Programming Languages

I am going to explain some very broad topics here in a very general way.

The C programming language is an unforgiving low-level language and things like memory management can be a nightmare. However, after assembler, it is probably the most efficient way to code in terms of performance. There are extensive shared libraries of important functions available, the libraries are normally platform specific. In Windows, the built-in libraries are called **Dynamic Link Libraries** or DLLs.

A program is written in _source code_ (in this case, C) and is compiled into object code, which is platform specific machine code with references to external libraries, called _assembler_. If I write code on my laptop and compile it for a different platform (e.g., an ARM processor), this is called _cross-compiling_.

Programs are usually made up from more than one module and may use code from standard libraries which we can _include_ in the program. The results of each module translation must be linked together to produce an executable program. A linker takes the object code and converts it into executable machine code.

<figure><img src="https://www.gitbook.com/cdn-cgi/image/dpr=2,width=760,onerror=redirect,format=auto/https%3A%2F%2Fcontent.gitbook.com%2Fcontent%2FnH7PRBdRDYCnYIXMxWHP%2Fblobs%2Frp65jZuZkwok7GlqTIPz%2Fimage.png" alt=""><figcaption></figcaption></figure>
