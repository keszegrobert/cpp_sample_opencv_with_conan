# cpp_sample_opencv_with_conan

Steps to reproduce:

```conan install . --install-folder build```

```cmake . -DCMAKE_TOOLCHAIN_FILE=build/conan_toolchain.cmake -DCMAKE_BUILD_TYPE=Release```

```cmake --build .```

```./DisplayImage logo.png```
