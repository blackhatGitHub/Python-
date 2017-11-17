#!/usr/bin/python
# -*- coding: UTF-8 -*-

Python 2.7.13 (v2.7.13:a06454b1afa1, Dec 17 2016, 20:42:59) [MSC v.1500 32 bit (Intel)] on win32
Type "copyright", "credits" or "license()" for more information.
>>>  tup1 = ('physics', 'chemistry', 1997, 2000);
 
  File "<pyshell#0>", line 2
    tup1 = ('physics', 'chemistry', 1997, 2000);
    ^
IndentationError: unexpected indent
>>> tup1 = ('physics', 'chemistry', 1997, 2000);
>>> tup2 = (1, 2, 3, 4, 5 );
>>> tup3 = "a", "b", "c", "d";
>>> tup1
('physics', 'chemistry', 1997, 2000)
>>> tup2
(1, 2, 3, 4, 5)
>>> tpu3

Traceback (most recent call last):
  File "<pyshell#6>", line 1, in <module>
    tpu3
NameError: name 'tpu3' is not defined
>>> tup3
('a', 'b', 'c', 'd')
>>> tup1 = ();
>>> tup1
()
>>> tup1(10,)

Traceback (most recent call last):
  File "<pyshell#10>", line 1, in <module>
    tup1(10,)
TypeError: 'tuple' object is not callable
>>> tup1(10,);

Traceback (most recent call last):
  File "<pyshell#11>", line 1, in <module>
    tup1(10,);
TypeError: 'tuple' object is not callable
>>> tup1 = (12, 34.56);
>>> tup2 = ('abc', 'xyz');
>>> tup3=tup1+tup2
>>> tup3
(12, 34.56, 'abc', 'xyz')
>>> tup3=tup2+tup1
>>> tup3
('abc', 'xyz', 12, 34.56)
>>> del tup3
>>> tup3

Traceback (most recent call last):
  File "<pyshell#19>", line 1, in <module>
    tup3
NameError: name 'tup3' is not defined
>>> 
