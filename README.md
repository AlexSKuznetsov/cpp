# Basic C++ GoogleTests setup with VS Code

### Manual build and run tests

1. Clone repo

```bash
git clone https://github.com/AlexSKuznetsov/cpp.git
```

2. Open terminal with project

```bash
cmake -S . -B build
```

```bash
cmake --build build
```

```bash
cd build && ctest
```

---

### Reference links

- GoogleTest using CMake - Quick start
  <br>
  https://google.github.io/googletest/quickstart-cmake.html

- C++ in VS Code: A Quick Guide
  <br>
  https://youtu.be/qeEcV6u1kV4

- CMake Target Debugging and Launching
  <br>
  https://vector-of-bool.github.io/docs/vscode-cmake-tools/debugging.html#debugging-launch-json

- Configure C/C++ debugging
  <br>
  https://code.visualstudio.com/docs/cpp/launch-json-reference

- CMake Tutorial
  <br>
  https://cmake.org/cmake/help/latest/guide/tutorial/index.html
