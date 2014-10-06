bashunit
========

Unit testing for BASH

All functionality is contained in the "bashunit" file.

Invoke it as follows:

 bashunit [FILE1] [FILE2] ...
 All test files must end in "test" and must be of type "shell script"
 If no test file is specified, bashunit searches in the current directory tree
 In each test file, bashunit runs every function whose name begins with "test"
 Tests may use the built-in "fail" and assertion functions
 (see list at the end of thie file)
 If a function "before_test" is defined, this will be executed before every test function

