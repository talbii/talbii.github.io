# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

Text `code();` more text.

Text *italic* **bold**.

Code block:

```c++
#include <stdio.h>
#include <stdlib.h>

int* get_arr(int);

int* get_arr(int size) {
    int* p = malloc(size * (sizeof p));
    int i = 0, x;
    
    for(; i < size; i++) {
        printf("\nEnter the value for [%d]: ", i);
        while(!scanf("%d", &x)) {
            printf("\nInput error. Please enter again:");
        }

        *(p + i) = x;
    }

    return p;
}
```

**Note**: this is actually C but renders better as C++.
