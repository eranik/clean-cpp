# copy-cpp
Base code to be used for new C++ projets.

### Provides following features:

* Duration for the operations.
* Showing messages in termianl and logging it to biuld.log.
* Simply biuld the project: ./build
* Clean the project with a simple argument: ./build c, ./build -c, ./build --clean
* Full build (clean, then build) the project with a simple argument: ./build f, ./build -f, ./build --full

After building the app, named my-app, will be copied to root directory of the project.

A useful CMakeLists.txt has been written for the project.

### VIM friendly development
It's recommended to use this project inside VIM:
1. vim -p ./build.log ./src/Main.cpp
2. Use vim command mode to build: **:!./build**
