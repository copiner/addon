### addon demo

You can install node-gyp using npm:
```
$ npm install -g node-gyp
```

Depending on your operating system, you will need to install:

On Unix

```
Python v2.7, v3.5, v3.6, or v3.7
make
A proper C/C++ compiler toolchain, like GCC
```


How to Use
To compile your native addon, first go to its root directory:
```
$ cd my_node_addon
```

The next step is to generate the appropriate project build files for the current platform. Use configure for that:
```
$ node-gyp configure
```


Now you will have either a Makefile (on Unix platforms). Next, invoke the build command:
```
$ node-gyp build
```
