# c-0923

### 01
基础语法

c语言是编译型语言
使用gcc编译器来编译

简单的例子
```
#include <stdio.h>
#include <stdlib.h>


int main(void) {
    printf("hello world!");
    exit(0);
}

```

使用gcc编译
```
gcc ./hello.c -o hello
```