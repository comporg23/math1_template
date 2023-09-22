

take a look at the files.

```
cat test.c
```

what is the difference between this file and this file: https://github.com/comporg23/math0_template/blob/main/test.c

now take a look at the `math32.s`.

that's an x86 assembly file.

there is an x86 makefile as well.

```
cat makefile32
```

now type

```
make -f makefile32
```

so this generates a x86 binary.

run it:

```
./test32
```

you got the answer.

now, how to do the same for x86_64?

what are the differences?

take a look at `math.s` file as well.

take a look at the `makefile` too.

as you've guessed (hopefully) if you type `make` the program will be compiled.

but `math.s` contains question marks that needs to be replaced.

the program will be compiled if `math.s` file will be at least syntactically correct.

but i want you to get the program to print result `42`. because that's the answer.

do something for that.

it'll help if you read comments in the `math.s` file.


so that's your task.
go!



p. s. should i remind you  that we provide you a cozy server for work?

p. p. s.

try to think why the c file has one version for both architectures?
