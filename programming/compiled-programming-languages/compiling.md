# Compiling

I use the gcc program in Linux to compile the source code file.

<figure><img src="https://www.gitbook.com/cdn-cgi/image/dpr=2,width=760,onerror=redirect,format=auto/https%3A%2F%2Fcontent.gitbook.com%2Fcontent%2FnH7PRBdRDYCnYIXMxWHP%2Fblobs%2FXbYokwFiQh64Kb9DkdJQ%2Fimage.png" alt=""><figcaption></figcaption></figure>

In my example

```
gcc -c -O2 -Wa,-al hello.c
```

* c tells gcc to compile or assemble source files, but not to link them
* O2 produces more fully optimized code
* Wa tells the compiler to pass the comma-separated list of options which follows it on to the assembler.
* The -al option is an assembler option to request an assembler listing.
