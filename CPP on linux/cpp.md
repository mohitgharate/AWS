# How to execute C++ program on Ubuntu linux instance By using amazon cloud service?
***

First login to your amazone cloud account and create an instance of ubuntu linux OS.\
first check setup is istalled or not.\
To check try the command :\
`gcc --version`

![Image](1.png)


If  it shows like above image then you have to install gcc in linux.


**Step-1 : Installation of GCC-C++**
***

command to install :\
`yum -y install gcc`

![Image](2.png)

command to update :\
`sudo yum update`

![Image](3.png)

Check the version again :\
`gcc --version`

![Image](4.png)

As might be seen from the output, the GCC version distributed by red hat 7 is 7.3.1-6 which is not the latest version of GCC.

You may also want to install gcc-c++. It will automatically include the C++ library and compile files with extensions that indicate they are C source as C++, instead of as C.

Enter this command to Install GCC-C++ :\
`yum -y install gcc-c++`

![Image](10.png)

*Now setup is ready to execute our first CPP program on our AWS LINUX Instance.*

**Step-2 : Implementation of CPP program**

Use any editor to type the code.\
For editor try command :\
e.g.\
`vi first.cpp`

![Image](6.png)

type "i" to go in insert mode.

![Image](7.png)

Write the code :\
e.g.\
#include\<iostream>\
using namespace std;
```
int main()\
{\
        cout<<"\n\nHello,\ World"<<endl;\
        return 0;\
} 
```
![Image](8.png)\
then press `esc` and then type `:wq!` to come out from editor.

**Step 3: Compilation of CPP Program file**

Use this command to Compile the CPP code and list the containt of current directory to see if the .out File is created or not.\
`g++ first.cpp` and then `ls -l` to see that *.out* file is created or not.

![Image](11.png)

**Step 4: Running the Compile code of CPP**

Use the command to get the output :\
`./a.out`

![Image](12.png)

*Congratulations!!!* You are done with the setup and running the program of cpp by using AWS Cloud Instance for Linux amazon ubuntu OS.
