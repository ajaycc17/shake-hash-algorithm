# An implementation of SHA-3 XOF SHAKE

## To run

After compilation, run the code on bash with the command-line arguments as follows:

```bash
-f filepath -d desired-output-bits
```

Following is an example of how the program is run:

```bash
gcc ./shake.c -o shake.o
./shake.o -f my\ file.pdf -d 256
```

In the above example, the filename is `my file.pdf`, to use blank space in command-line argument an escape character i.e. `\` is used before blank space.
