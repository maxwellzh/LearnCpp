# Test Your Compiler with C++17 Support

**Compile**

```shell
# change to current workspace if you're not
cd 0.12-testcompiler/

g++ -o testcompiler.o testcompiler.cpp -std=c++17
```

**Execute**

```shell
./testcompiler.o
# output would be:
# >>> hello 3 6
# >>> 3
```