# Building a relational database from scratch in C++

The goal of this project is to learn how a relational database work under the hood by building it from scratch.
It's also an opportunity to level up in C++

## References

https://build-your-own.org/database/

## Installation

You will need to install the following package to run the project

```
sudo apt install cmake
sudo apt install gcc
```

create a debug and a build folder

```project folder
├── .gitattributes
├── .gitignore
├── CMakeLists.txt
├── README.md
├── build/
├── debug/
└── src/
    └── main.cpp
```

### Build and launch in Debug

```
cd debug
cmake -DCMAKE_BUILD_TYPE=Debug ..
cmake --build .

# launch
./DatabaseFromScratch
```

Or use vscode launch.json to debug ( `sudo apt install gdb` required)
