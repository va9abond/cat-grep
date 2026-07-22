# Build

Для сборки утилиты `cat` используйте:
```bash
$ make
```

# Tests

Для запуска тестов используйте (`python3` required):
```bash
make tests
```

# Usage

```bash
$ ./cat --help
Usage: cat [OPTION]... [FILE]...
Concatenate FILE(s), or standard input, to standard output.

-A, --show-all           equivalent to -vET
-b, --number-nonblank    number nonempty output lines
-e                       equivalent to -vE
-E, --show-ends          display $ at end of each line
-n, --number             number all output lines
-s, --squeeze-blank      suppress repeated empty output lines
-t                       equivalent to -vT
-T, --show-tabs          display TAB characters as ^I
-u                       (ignored)
-v, --show-nonprinting   use ^ and M- notation, except for LFD and TAB
-h, --help               display this help and exit

Examples:
cat f - g  Output f's contents, then standard input, then g's contents.
cat        Copy standard input to standard output.

Author: Rustem Sirazetdinov
```
