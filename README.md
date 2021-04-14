# favorite-cpp-resources

## C++14 libs
* https://github.com/fmtlib/fmt [[conan]](https://conan.io/center/fmt)

  `std::format` from C++20 available in C++14
    
* https://github.com/catchorg/Catch2.git [[conan]](https://conan.io/center/catch2)

  For unit testing
  
* https://github.com/google/googletest [[conan]](https://conan.io/center/gtest)

  For unit testing and mocking
  
* https://github.com/eranpeer/FakeIt [[conan]](https://conan.io/center/fakeit)

  For mocking
  
* https://github.com/rollbear/trompeloeil [[conan]](https://conan.io/center/trompeloeil)

  For mocking
 
* https://github.com/mapbox/variant.git

  For a close implementation of `std::variant` and `std::optional` (in C++17) available with C++14
  
* https://github.com/ericniebler/range-v3 [[conan]](https://conan.io/center/range-v3)

  Range library for C++14/17/20, basis for C++20's std::ranges
  
* https://github.com/gabime/spdlog [[conan]](https://conan.io/center/spdlog)

  Fast C++ logging library.
  
## C++17

* https://github.com/hanickadot/compile-time-regular-expressions [[conan]](https://conan.io/center/ctre)

  Compile time very efficient REGEX
  
* https://github.com/xroche/stringswitch

  Efficient switch on string
  
* https://github.com/Neargye/magic_enum [[conan]](https://conan.io/center/magic_enum)

  Enum static reflection
  
## Alternative STL

* https://github.com/facebook/folly [[conan]](https://conan.io/center/folly)

  Facebook Open-source Library
  
* https://github.com/electronicarts/EASTL [[conan]](https://conan.io/center/eastl)

  Electronic Arts Standard Template Library
  
* https://github.com/bloomberg/bde/tree/master/groups/bsl

  BSL (Basic Standard Library) part of BDE Libraries
  
* https://github.com/abseil/abseil-cpp [[conan]](https://conan.io/center/abseil)

  Abseil : C++ Common Libraries: 
  
  *[...] designed to augment the C++ standard library [...] collected from Google's own C++ code base*
  
## Functional Programming in C++

* https://github.com/arximboldi/lager
  
  Value-oriented design using the unidirectional data-flow architecture

* https://github.com/arximboldi/immer
  
  Postmodern immutable and persistent data structures for C++
  
* https://github.com/serge-sans-paille/frozen [[conan]](https://conan.io/center/frozen)

  Header-only library that provides 0 cost initialization for immutable containers, fixed-size containers, and various algorithms.
  
* https://github.com/Dobiasd/FunctionalPlus

  Functional Programming Library for C++.

* https://github.com/graninas/cpp_functional_programming

  List of materials about functional programming in C++
  
* https://github.com/TartanLlama/expected

  C++11/14/17 std::expected with functional-style extensions

* Good samples (need more analysis)
  * https://gist.github.com/splinterofchaos/4112114
  * https://github.com/toby-allsopp/coroutine_monad
  * https://github.com/dkormalev/cefal (C++20)
  * https://github.com/dkormalev/asynqro
  * https://github.com/BartoszMilewski/Okasaki ([aside talk](https://github.com/BartoszMilewski/Okasaki/raw/872408f10d0c3de0e0ab66140afdd10fe5cf0b23/Functional%20Data%20Structures.key))
  * https://github.com/graninas/cpp_stm_free
  * https://github.com/loopperfect/neither

## Tools

### Profiler

* https://github.com/yse/easy_profiler [[conan]](https://conan.io/center/easy_profiler)
  * to build it on macOS, use:
  ```
  cmake -DCMAKE_PREFIX_PATH=/usr/local/Cellar/qt@5/5.15.2 -DCMAKE_CXX_COMPILER=g++-9 -DCMAKE_C_COMPILER=gcc-9 -DCMAKE_BUILD_TYPE="Release" ..
  ```

* https://github.com/wolfpld/tracy
  * to build it on macOS, use:
  ```
  brew install freetype capstone gtk glfw
  make -C profiler/build/unix release
  ```
  * to build it on Linux Ubuntu 20.02, use:
  ```
  apt install libcapstone-dev libtbb-dev libglfw3-dev libfreetype6-dev libgtk-3-dev
  make -C profiler/build/unix release  
  ```

* https://github.com/bombomby/optick

### Benchmark

* https://github.com/google/benchmark [[conan]](https://conan.io/center/benchmark)

### Experimental

* Reflection with Circle : https://www.circle-lang.org

## Bits operations

 * http://graphics.stanford.edu/~seander/bithacks.html
 * http://realtimecollisiondetection.net/blog/?p=78
 * https://bits.stephan-brumme.com
 * http://aggregate.org/MAGIC/

## Book references

 * https://stackoverflow.com/questions/388242/the-definitive-c-book-guide-and-list?answertab=active#tab-top

## List of lists

 * https://github.com/fffaraz/awesome-cpp
 
 * https://github.com/rigtorp/awesome-modern-cpp
 
## Ref cards

* GDB/LLDB command command map : https://lldb.llvm.org/use/map.html

# unexpected optimizations

* ["Three Optimization Tips For C++" by Andrei Alexandrescu](https://archive.org/details/AndreiAlexandrescu-Three-Optimization-Tips) [pdf](https://ia801703.us.archive.org/3/items/AndreiAlexandrescu-Three-Optimization-Tips/Main-slides.pdf)
* [“Speed Is Found In The Minds of People" by Andrei Alexandrescu](https://youtu.be/FJJTYQYB1JQ) [pdf](https://github.com/CppCon/CppCon2019/blob/master/Presentations/speed_is_found_in_the_minds_of_people/speed_is_found_in_the_minds_of_people__andrei_alexandrescu__cppcon_2019.pdf)
