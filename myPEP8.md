# my PEP8

1. Max column number to be limited to 80, use black w/ VSStudio.
2. Ident with four spaces

# Naming conventions
3. Snake case for variable names for e.g. hello_world it is python after all :)
4. Constants are all uppper snake cases HELLO_WORLD
5. File names are one single word in small letter hello_world.py
6. Function name is hello_world(), same snake case.
7. Class names are CamelCase class HelloWorld
8. Exceptoins are also in CamelCase
9. First parameter to a constructor always be to named as self
10. Class methods first parameter must be cls.
11. Two blank lines between classes and functions, howevere one blank line between methods within the same class

# imports
12. Always at the top of the file.
13. One module imported in one line
14. from  os import stat, path is OK
15. from os import * is NOT OK
16. imports can be after the docstring which is """

# Quotations
17. Always use single quotataion marks


# Whitespace
18. No white spaces before or after index or tuple or trailing comma or end of method name
19. One witespace on each side of equal sign
20. One whitespace before and after an operator
21. When showing prcedence of operators no white spaces
22. a = b + c is OK
23. a = (b+c) * (d+e) is OK
24. def complex(real, imag=0):
25.     return magic(r=real,i=imag) is OK
26. blah blah <b><b>#<b>This is an inline comment is OK

# Type checking
27. if foo is not 'X':
        pass
is OK
28. if foo is "x::
        pass
is OK

# Exceptions
29. Always catch a particular exception by name and not a catch all.

Credits to https://youtu.be/D4_s3q038I0 



