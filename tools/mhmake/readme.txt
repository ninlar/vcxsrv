To build this tool you first need to install Visaul C++ Studio .NET 2003,
Visual Studio 2008 or Visual Studio 2010.

Open the mhmake.sln, mhmakevc6.sln or mhmakevc10.sln file in Visual Studio
depending on the version of Visual Studio and compile for Debug and for
Release.
2 executables are generated by this process:
- Release\mhmake.exe : gnu make compatible make program with some specific
  extension is make the build process faster.

- Debug\mhmake_dbg.exe  : Has the same functionality but does extra
  error checking on makefiles and has extra debugging options. This one
  is advised to be used when creating makefiles. When the makefiles are
  fully debugging mhmake.exe is a better choise because here the build
  process will be faster. mhmake.exe is more likely to crash when badly
  written makefiles are passed as input.

To build with kdevelop4 on linux
- run genkdev4.sh

- run 'make' and 'make install' in the build and build.dbg directories

or

- open mhmake.kdev4 and build configuration build and build.dbg
- run 'make install' in the build and build.dbg directories (as root)

