# Welcome to the JDK!

For build instructions please see the
[online documentation](https://openjdk.java.net/groups/build/doc/building.html),
or either of these files:

- [doc/building.html](doc/building.html) (html version)
- [doc/building.md](doc/building.md) (markdown version)

See <https://openjdk.java.net/> for more information about
the OpenJDK Community and the JDK.



# Jong Memo
you might experience a number of error to compile openJDK in your macOS.
there're some tips to compile openJDK.


1. openJDK version
if you're using M1 or upper version, openJDK 17 and 21 started supporting compilation in macOS, so 17 or upper version is recommended to comiple in M1 max.

2. git repository
openJDK 17 still has many bugs for macOS. you better git clone from openJDK17u version.
https://github.com/openjdk/jdk17u

3. references to fix bugs
here are some referecen links to fix the compile error.
https://aeffy.icu/2023/05/15/InsideTheJVM/insideTheJVMOne/
https://github.com/openjdk/jdk18u/pull/99


