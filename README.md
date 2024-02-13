# CppTamplate
Use this template to start a new C++ project. It is a CMake project with the following tools:

## Clang-tidy
Help to find bugs, it is a static analysis tool. It is a part of the LLVM project. It is a linter for C++. Checks bugs at compile time.

Use it from build button in vscode, select the correct build target.

## Sanitizers
Help to find bugs, it is a dynamic analysis tool. It is a part of the LLVM project. It is a runtime tool.

## Doxygen
It is a documentation tool.

Use it from build button in vscode, select docs build target.

## Clang-format
It is a code formatter for source file. It is a part of the LLVM project.

Use it from build button in vscode, select the run_clang_format build target.

## CMake-format
It is a code formatter of CMakeLists.txt files.

Use it from build button in vscode, select the run_cmake_format build target.

## Code Coverage
It is a tool to find out how much of the code is covered by the test cases.

Use it from build button in vscode, select the coverage build target.

## Pre-commit
It is a tool to run the clang-format, cmake-format, and doxygen before the commit.

## GitHub Actions
It is a tool to run the clang-tidy, sanitizers, doxygen, and code coverage on the GitHub server.
