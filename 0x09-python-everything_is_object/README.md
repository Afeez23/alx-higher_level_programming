3
n - Everything is object



Requirements Python Scripts Allowed editors: vi, vim, emacs All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5) All your files should end with a new line The first line of all your files should be exactly #!/usr/bin/python3 A README.md file, at the root of the folder of the project, is mandatory Your code should use the pycodestyle (version 2.8.*) All your files must be executable The length of your files will be tested using wc .txt Answer Files Only one line No Shebang All your files should end with a new line.



Who am I? mandatory What function would you use to print the type of an object?

Write the name of the function in the file, without ().



Where are you? mandatory How do you get the variable identifier (which is the memory address in the CPython implementation)?

Write the name of the function in the file, without ().



Right count mandatory In the following code, do a and b point to the same object? Answer with Yes or No.

a = 89 b = 100



Right count = mandatory In the following code, do a and b point to the same object? Answer with Yes or No.

a = 89 b = 89



Right count =+ mandatory In the following code, do a and b point to the same object? Answer with Yes or No.

a = 89 b = a + 1



Is equal mandatory What do these 3 lines print?

s1 = "Best School" s2 = s1 print(s1 == s2)



Is the same mandatory What do these 3 lines print?

s1 = "Best" s2 = s1 print(s1 is s2)



Is really equal mandatory What do these 3 lines print?

s1 = "Best School" s2 = "Best School" print(s1 == s2).



Is really the same mandatory What do these 3 lines print?

s1 = "Best School" s2 = "Best School" print(s1 is s2)



And with a list, is it equal mandatory What do these 3 lines print?

l1 = [1, 2, 3] l2 = [1, 2, 3] print(l1 == l2)



And with a list, is it the same mandatory What do these 3 lines print?

l1 = [1, 2, 3] l2 = [1, 2, 3] print(l1 is l2)



And with a list, is it really equal mandatory What do these 3 lines print?

l1 = [1, 2, 3] l2 = l1 print(l1 == l2)



And with a list, is it really the same mandatory What do these 3 lines print?

l1 = [1, 2, 3] l2 = l1 print(l1 is l2)



List append mandatory What does this script print?

l1 = [1, 2, 3] l2 = l1 l1.append(4) print(l2)



List add mandatory What does this script print?

l1 = [1, 2, 3] l2 = l1 l1 = l1 + [4] print(l2)



Integer incrementation mandatory What does this script print?

def increment(n): n += 1



a = 1 increment(a) print(a)



List incrementation mandatory What does this script print?

def increment(n): n.append(4)



l = [1, 2, 3] increment(l) print(l)



List assignation mandatory What does this script print?

def assign_value(n, v): n = v



l1 = [1, 2, 3] l2 = [4, 5, 6] assign_value(l1, l2) print(l1)



Copy a list object mandatory Write a function def copy_list(l): that returns a copy of a list.

The input list can contain any type of objects Your file should be maximum 3-line long (no documentation needed) You are not allowed to import any module



Tuple or not? mandatory a = () Is a a tuple? Answer with Yes or No.



Tuple or not? mandatory a = (1, 2) Is a a tuple? Answer with Yes or No.



Tuple or not? mandatory a = (1) Is a a tuple? Answer with Yes or No.



Tuple or not? mandatory a = (1, ) Is a a tuple? Answer with Yes or No.



Who I am? mandatory What does this script print?



a = (1) b = (1) a is b



Tuple or not mandatory What does this script print?

a = (1, 2) b = (1, 2) a is b



Empty is not empty mandatory What does this script print?

a = () b = () a is b



Still the same? mandatory

id(a) 139926795932424 a [1, 2, 3, 4] a = a + [5] id(a)



Same or not? mandatory

a [1, 2, 3] id (a) 139926795932424 a += [4] id(a)



#pythonic #advanced Write a function magic_string() that returns a string “BestSchool” n times the number of the iteration (see code):

Format: see example Your file should be maximum 4-line long (no documentation needed) You are not allowed to import any module



Low memory cost #advanced Write a class LockedClass with no class or object attribute, that prevents the user from dynamically creating new instance attributes, except if the new instance attribute is called first_name.

You are not allowed to import any module



int 1/3 #advanced julien@ubuntu:/python3$ cat int.py a = 1 b = 1 julien@ubuntu:/python3$



int 2/3 #advanced julien@ubuntu:/python3$ cat int.py a = 1024 b = 1024 del a del b c = 1024 julien@ubuntu:/python3$



int 3/3 #advanced julien@twix:/tmp/so$ cat int.py print("I") print("Love") print("Python") julien@ubuntu:/tmp/so$



Clear strings #advanced guillaume@ubuntu:/python3$ cat string.py a = "SCHL" b = "SCHL" del a del b c = "SCHL" guillaume@ubuntu:/python3$
