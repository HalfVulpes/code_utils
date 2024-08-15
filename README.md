# code_utils noetic version
code_utils opencv 4 and ros noetic version

Adapted from https://github.com/gaowenliang/code_utils

Changed for OpenCV 4 and ros noetic 

![image-20240815151353552](./assets/image-20240815151353552.png)



If following happens:

```shell
code_utils/include/code_utils/backward.hpp:216:12: fatal error: elfutils/libdw.h:
No such file or directory
216 | # include <elfutils/libdw.h>
```

please install 

```
sudo apt-get install libdw-dev
```

