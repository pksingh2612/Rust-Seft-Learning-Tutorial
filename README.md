# Rust-Seft-Learning-Tutorial-
This repository serves as a journal to document, track, and share my journey of learning Rust from the ground up.

# Learning Matters & References:

## The Rust Programming Language - RustBook
https://doc.rust-lang.org/stable/book/title-page.html

## YT Rust Programming Language by Priyush Garg
https://www.youtube.com/playlist?list=PLinedj3B30sA_M0oxCRgFzPzEMX3CSfT5

# System Requirements
## OS - Windows (that i am using)

# Issue While installing RUST in my local system 

## Issue 1
error: linker `link.exe` not found
  |
  = note: program not found

note: the msvc targets depend on the msvc linker but `link.exe` was not found

note: please ensure that Visual Studio 2017 or later, or Build Tools for Visual Studio were installed with   = note: program not found

note: the msvc targets depend on the msvc linker but `link.exe` was not found
  = note: program not found

  = note: program not found
  = note: program not found
  = note: program not found

note: the msvc targets depend on the msvc linker but `link.exe` was not found

note: please ensure that Visual Studio 2017 or later, or Build Tools for Visual Studio were installed with the Visual C++ option.

note: VS Code is a different product, and is not sufficient.

  = note: program not found

note: the msvc targets depend on the msvc linker but `link.exe` was not found

note: please ensure that Visual Studio 2017 or later, or Build Tools for Visual Studio were installed with the Visual C++ option.

note: VS Code is a different product, and is not sufficient.
  = note: program not found

note: the msvc targets depend on the msvc linker but `link.exe` was not found

note: please ensure that Visual Studio 2017 or later, or Build Tools for Visual Studio were installed with the Visual C++ option.

  = note: program not found

note: the msvc targets depend on the msvc linker but `link.exe` was not found

  = note: program not found

  = note: program not found

note: the msvc targets depend on the msvc linker but `link.exe` was not found

note: please ensure that Visual Studio 2017 or later, or Build Tools for Visual Studio were installed with the Visual C++ option.

note: VS Code is a different product, and is not sufficient.

error: aborting due to 1 previous error

Solution : https://rust-lang.github.io/rustup/installation/windows-msvc.html
In short,
You will also need a linker, which is a program that Rust uses to join its compiled outputs into one file. It is likely you already have one. If you get linker errors, you should install a C compiler, which will typically include a linker. A C compiler is also useful because some common Rust packages depend on C code and will need a C compiler.

If you’d like a more minimal install (and won’t be doing C++ development) then you can use the “Individual Components” tab to select just the essentials, which are:

MSVC v143 - VS 2022 C++ x64/x86 build tools (Latest)
Windows 11 SDK (10.0.22621.0)
Note that the specific version of the Windows SDK doesn’t matter for pure Rust code but if using C++ as well you’ll likely want either the latest or whichever version is required by the C++ project (or both).


# To compile the program
rustc program-file-name.rs

# To execute the program
program-file-name

# To format your code in a particular style
rustfmt program-file-name.rs

#### Note: The main.pdb -  a file containing debugging information
