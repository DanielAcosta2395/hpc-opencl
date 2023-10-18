https://github.com/KhronosGroup/OpenCL-Guide/blob/main/chapters/getting_started_windows.md#compiling-on-the-command-line

```cl.exe /nologo /TC /W4 /DCL_TARGET_OPENCL_VERSION=100 /I ./OpenCL-SDK\include\ Main.c /Fe:HelloOpenCL /link /LIBPATH:./OpenCL-SDK\lib OpenCL.lib```

```cmake -A x64 -S . -B .\build -D CMAKE_PREFIX_PATH=\prjs\hpc\OpenCL-SDK\```
