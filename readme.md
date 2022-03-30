# Mobile Development with Flutter

## Flutter Installation on windows 10

## Download Flutter SDK

Link: <https://flutter.dev/docs/get-started/install/windows>

- Extract the zip file and place the contained flutter in the desired installation location for the Flutter SDK (for example, C:\Users\<your-user-name>\Documents).

- Update your path

- If you wish to run Flutter commands in the regular Windows console, take these steps to add Flutter to the PATH environment variable:

  - From the Start search bar, enter ‘env’ and select Edit environment variables for your account.

  - Under User variables check if there is an entry called Path:

  - If the entry exists, append the full path to flutter\bin using ; as a separator from existing values.

  - If the entry doesn’t exist, create a new user variable named Path with the full path to flutter\bin as its value.

  - After that run $ flutter --doctor on cmd. if it runs you are setup for the session


## Install Flutter on Linux


### Download Flutter SDK

Link: <https://flutter.dev/docs/get-started/install/linux>

1. Extract the file in the desired location, for example:

- cd ~/development/flutter

- tar xf ~/Downloads/flutter_linux_2.10.4-stable.tar.xz

2. Add the flutter tool to your path:

- export PATH="$PATH:`pwd`/flutter/bin"


### Additional requirements for Flutter on Linux

For Linux desktop development, you need the following in addition to the Flutter SDK:

 *  Clang
 *  CMake
 *  GTK development headers
 *  Ninja build
 *  pkg-config
 *  liblzma-dev This might be necessary

Run the following command

sudo apt-get install clang cmake ninja-build pkg-config libgtk-3-dev liblzma-dev

#### Enable desktop support
 - flutter config --enable-linux-desktop


### You need to have installed one of the latest google chrome