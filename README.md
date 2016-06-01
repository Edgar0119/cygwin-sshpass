# Cygwin-sshpass
Run sshpass on Windows via Cygwin

# Build requirements package (use latest verison)
* autoconf
* automake
* binutils
* cygport
* gcc-core
* make

You can use apt-cyg to install above packages

install apt-cyg to your cygwin (https://github.com/transcode-open/apt-cyg)

Run apt-cyg install XXXXXX to install above requirements package

# Build instructions
$ git clone https://github.com/Edgar0119/cygwin-sshpass.git cygwin-sshpass

$ cd cygwin-sshpass

$ tar -zxvf sshpass-1.05.tar.gz

$ cd sshpass-1.05

$ bash ./configure

$ make

Now you can see sshpass.exe in the folder

Then move sshpass.exe to ${CygwinRoot}\bin\sshpass.exe

# Reference
https://github.com/fd00/yacp/tree/master/sshpass
