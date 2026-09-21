# potato-master369

Here's a very normal, and totally portable (not) Hello World implementation in C!

```
#include <unistd.h>
#include <stdlib.h>

int main(void)
{
  char msg[] = "Hello, world!\n";
  write(STDOUT_FILENO, msg, sizeof(msg) - 1);
  return EXIT_SUCCESS;
}
```  
