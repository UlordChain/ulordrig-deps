# ulordrig-deps      
## Content    
Static libraries and corresponding header files of UlordRig dependencies.         
* [libuv](https://github.com/libuv/libuv) 1.20.3    
* [libmicrohttpd](https://www.gnu.org/software/libmicrohttpd) 0.9.59    

Only **gcc/x86** supports Windows XP/2003.
## Usage    
### MSYS2    
- x64 `"c:\Program Files\CMake\bin\cmake.exe" .. -G "Unix Makefiles" -DULORDRIG_DEPS=c:/ulordrig-deps/gcc/x64`    
- x86 `"c:\Program Files\CMake\bin\cmake.exe" .. -G "Unix Makefiles" -DULORDRIG_DEPS=c:/ulordrig-deps/gcc/x86`    
