##MONTY

## Description

It is a interpreter for Monty ByteCodes files.

***

## Usage

1. Clone the repository:
```console
https://github.com/zoebelete/monty.git
```

2. Enter at directory
```console
cd monty
```

3. Compile:
```console
gcc -Wall -Werror -Wextra -pedantic *.c -o monty
```

4. Execute:
```console
./monty file.m
//The file contains the bytcode instructions for example
cat -e 000.m
push 0$
push 1$
push 2$
  push 3$
                   pall    $
push 4$
    push 5    $
      push    6        $
pall$
```
```

### Autor

zoebelete
