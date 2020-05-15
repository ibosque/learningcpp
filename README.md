# learningcpp

Go to the directory where you want to keep your files
cd programs/

Create the file, instead of using gedit, i am using atom and also i am not writing sudo at the beginning
```bash
atom hello.cpp
```
// Your First C++ Program

#include <iostream>

int main() {
    std::cout << "Hello World!";
    return 0;
}


 Compile the program  Where first is the executable or object file of first.c program.
 $ sudo g++ -o hello hello.cpp

 % Run it

  ./hello 
