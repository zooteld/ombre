Building Ombre
==============

Build Dependencies
------------------

You will need:

* on Debian Linux distros `sudo apt-get install build-essential cmake libboost-all-dev miniupnpc libunbound-dev graphviz doxygen libunwind8-dev pkg-config libssl-dev libcurl4-openssl-dev libgtest-dev libreadline-dev libminiupnpc-dev libzmq3-dev libsodium-dev libsodium18 libsodium-dbg `

Download
--------

Download the latest source code from `https://github.com/ombre-projects/ombre/releases`

Using command line to download
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`wget https://github.com/ombre-projects/ombre/archive/1.4.1.zip`

or 

[curl](https://curl.haxx.se/download.html)

`curl https://github.com/ombre-projects/ombre/archive/1.4.1.zip`

Then extract the zip file.

Using git
~~~~~~~~~

`git clone https://github.com/ombre-projects/ombre.git`


Compiling
---------

```sh
cd ombre 
make
```


We recommend using make’s parallel build feature to accelerate the compilation process. For instance:

```
make -j 4
```

