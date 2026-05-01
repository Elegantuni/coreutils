# coreutils
coreutils with cat and tac modification<br>
<br>
Pass cat or tac -p and then a file(s). <br>
It prints the name of the file the output is from. <br>

To compile:
$ ./configure --prefix=/usr
$ sed -i "s/-Werror//g" Makefile
$ make
$ sudo make install
