# Stringify

Stringify all the things!

```c
#include <stdio.h>
#include <stringify.h>

int main() {
    printf("[%s:%s]: %s\r\n", __FILE__, stringify(__LINE__), stringify(Hello World!));
    return 0;
}
```
