# Tic_Tac_Toe_Using_C-
Tic Tac Toe game using C++. Additional features include adding in a counter that counts the number of moves to win the game.

In order to run this program, it is recommended to download the MinGW Compiler to install the GCC and G++ compilers run C and C++ programs, respectively. Free Code Camp has a great tutorial on how to get started downloading a compiler for C++: https://www.freecodecamp.org/news/how-to-install-c-and-cpp-compiler-on-windows/.

After downloading the MinGW Compiler, it is recommended to use some kind of distribution system to run the program. The distribution system that I used was Windows-Subsystem for Linux (WSL), but using other distribution systems such as Ubuntu or Debian is also fine.

After forking this repository to your computer, go to the folder path containing this file, then first compile the program. If you are using WSL, type in the command "g++ Tic_Tac_Toe.cpp". After compiling the program, then type in the command "a.out" or "./a.out" to receive user input. The difference "a.out" and "./a.out" is that "a.out" will check files on your PATH, while prepending "a.out" with "./" tells the system to look for a file in your currently selected directory. This is important to understand, as compiling the program will not automatically give you a user input prompt, unlike with Java or Python.
