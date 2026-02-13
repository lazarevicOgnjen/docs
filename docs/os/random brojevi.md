```c

#include <stdlib.h>
#include <time.h>

// Call once at start to get true randomness
srand(time(NULL));

// Get random number
int num = rand();        // 0 to RAND_MAX
int dice = rand() % 6;   // 0 to 5
int x = rand() % 6 + 1; // 1 to 6

```
