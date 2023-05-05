# 42sh

POSIX standarts compliant shell implementation in C language. 

Implementation of several commands :

- if, else, elif, fi
- while / until, do, done
- true / false
- echo
- cd
- builtin commands

## Installation

To download our project:

```
wget https://github.com/TRKirua/42sh/archive/refs/heads/main.zip -O "42sh.zip" &&
unzip ./"42sh.zip" &&
rm ./"42sh.zip"
```

To compile our project:

```
meson setup builddir
```

Then:

```
ninja -C builddir
```

## Usage

To run our project, you have several options:

To launch in interactive mode, just do:

```
./builddir/42sh
```

To launch by using a file:

```
./builddir/42sh <your_file>
```

Or directly using stdin with a file:

```
./builddir/42sh < <your_file>
```

You can also do:

```
./builddir/42sh -c "<your_command(s)>"
```

## Clean project

To clean the project:

```
rm -r builddir
```

## Credits :
- [BARBERIS Emon](https://github.com/EmonBar)
- [EKICI Enes](https://github.com/TRKirua)
- [ABOU-AL-TOUT Samy](https://github.com/locovamos)
- [TWAGIRAKRISTU Jean-Marc](https://github.com/Tamiavison)
