# Усложненный make-file.  Введены переменные для параметров компиляции и исполняемых файлов

.PHONY: all debug release clean

release_flags = -O2 -Wall -DNDEBUG
debug_flags   = -g -O0 -Wall
release_exec  = hello
debug_exec  = hello-dbg
source      = hello.cpp

all: debug release

debug: $(debug_exec)

hello-dbg: $(source) 
        g++ $(debug_flags) hello.cpp -o $(debug_exec) 

release: $(release_exec)

hello: $(source) 
        g++ $(release_flags) hello.cpp -o $(release_exec)

clean:
        rm -f $(release_exec) $(debug_exec) 
~                                                                                                                                                                        
~                                                                                                                                                                        
~                                                                                                                                                                        
~                                                                                                                                                                        
~                                                                                                                                                                        
~                                                                                                                                                                        
~                                                                                                                                                                        
~                                                                                                                                                                        
                                                                                                                                                       2,0-1        Весь

