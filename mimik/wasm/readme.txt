compile openssl for wasm

emconfigure ./config no-asm --prefix=install_directory no-zlib no-threads no-shared
make
make install

if prompting errors during make, modify Makefile to fix the compiling errors. 
