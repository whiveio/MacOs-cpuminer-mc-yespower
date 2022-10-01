# Whive Cpu-miner for MacOs

# Build

### MacOS
Run the following commands in your mac terminal:
```bash

$ git clone https://github.com/whiveio/MacOs-cpuminer-mc-yespower 

$ brew install curl

$ brew install autoconf

$ brew install automake

$ cd MacOs-cpuminer-mc-yespower 

$ ./autogen.sh

$ ./nomacro.pl

$ ./configure CFLAGS="-O3 -march=native -funroll-loops -fomit-frame-pointer" 

$ make

```


# Run

### Mac
yespower solo mining example: ( -u for username -p password, change them to your own)
```bash
./minerd -a yespower -o http://127.0.0.1:1867 -u whive -p pass --coinbase-addr= <YOUR WHIVE ADDRESS>
```


