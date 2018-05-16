Contributing guide
==================

License
-------

The source file should contains a license header. See the existing files
as an example.

Python coding style
-------------------

Changes to Python code should conform to [PEP8 Style Guide for Python
Code](https://www.python.org/dev/peps/pep-0008/).

You can use pycodestyle to check the style.

C++ coding style
----------------

Changes to C++ code should conform to [Google C++ Style
Guide](https://google.github.io/styleguide/cppguide.html).

You can use cpplint to check the style and use clang-format to format
the code:

```sh
clang-format -style="{BasedOnStyle: google,            \
                      DerivePointerAlignment: false,   \
                      PointerAlignment: Right,         \
                      BinPackParameters: false}" $file
```
