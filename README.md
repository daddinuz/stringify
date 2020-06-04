# Stringify

Stringify all the things!

```c
#include <stdio.h>
#include <stringify.h>

int main() {
    printf("['%s:%s']: %s\r\n", __FILE__, stringify_lazyQuote(__LINE__), stringify_quote(Hello World!));
    return 0;
}
```
