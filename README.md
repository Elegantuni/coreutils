# coreutils
coreutils with cat and tac modification<br>
<br>
Pass cat or tac -p and then a file(s). <br>
It prints the name of the file the output is from. <br>
<br>
To compile: <br>
$ ./configure --prefix=/usr <br>
$ sed -i "s/-Werror//g" Makefile <br>
$ make <br>
$ sudo make install <br>
