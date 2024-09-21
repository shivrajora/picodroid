# Version 0.1 #

## Goals: ##

1. Boot into a "launcher"
2. Support both host simulator and rp2040 MCU targets

## Things to do: ##

1. Initialize system thread and app main thread
2. Add a graphics library (maybe lvgl?).
3. Add a lightweight JVM.
4. Add a lightweight JNI interface so that all Java utilities can be implemented in C++.
5. Implement Android classes in C++.
6. Compile a minimum Android app into a compressed binary blob "apk".
7. Add a mechanism to load and executte the binary blob.