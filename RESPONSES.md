# CISC230 - Steven Petrik

## factorial2.cpp

- input/parameter impacting number of calls
unsigned int n: this parameter takes a positive integer that changes the number of calls due to its numerical value

- 3 specific examples of input/parameter and number of calls
unsigned int n = 5: 6 function calls
unsigned int n = 4: 5 function calls
unsigned int n = 9: 10 function calls

- number of recursive calls when input/parameter is *n*
number of recursive calls = n + 1

## ireverse2.cpp

- input/parameter impacting number of calls
unsigned int n: this parameter takes a positive integer that changes the number of calls due to its character size

- 3 specific examples of input/parameter and number of calls
unsigned int n = 5: 2 function calls
unsigned int n = 43: 3 function calls
unsigned int n = 956: 4 function calls

- number of recursive calls when input/parameter is *n*
number of recursive calls = to_string(n).length() + 1

## sreverse2.cpp

- input/parameter impacting number of calls
const string& s: This parameter accepts a string which the length affects the amount of calls

- 3 specific examples of input/parameter and number of calls
const string& s = "hello": 4
const string& s = "hello world": 10
const string& s = "hello World?": 11

- number of recursive calls when input/parameter is *n*
number of recursive calls = n.length() - 1


## permute.cpp

- input/parameter impacting number of calls
const string& str: This parameter accepts a string in which the length affects the amount of calls

- 3 specific examples of input/parameter and number of calls
const string& str = cat: 16
const string& str = four: 65
const string& str = fives: 326

- number of recursive calls when input/parameter is *n*
number of recursive calls is modeled by the recursive equation where f(0) = 1 and
f(n.length()) = n.length()(f(n.length - 1)) + 1

## tower.cpp

- input/parameter impacting number of calls
int n_disks: this parameter takes a positive integer that changes the number of calls due to its numerical value

- 3 specific examples of input/parameter and number of calls
int n_disks = 3: 15
int n_disks = 4: 31
int n_disks = 5: 63

- number of recursive calls when input/parameter is *n*
number of recursive calls = 2(2^n)-1

## fibonacci2.cpp (presented in video lesson)

- input/parameter impacting number of calls
unsigned int n: this parameter takes a positive integer that changes the number of calls due to its numerical value

- 3 specific examples of input/parameter and number of calls
unsigned int n = 2: 2
unsigned int n = 8: 20
unsigned int n = 10: 26

- number of recursive calls when input/parameter is *n*
number of recursive calls = |3n-4|