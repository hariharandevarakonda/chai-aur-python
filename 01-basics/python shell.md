PS C:\Users\harih\OneDrive\Desktop\chai aur python\01-basics> ls

    Directory: C:\Users\harih\OneDrive\Desktop\chai aur python\01-basics

Mode LastWriteTime Length Name

---

da---l 15-10-2024 06:58 PM **pycache**
-a---l 15-10-2024 06:58 PM 57 chai.py
-a---l 05-11-2024 08:09 PM 561 datatypes.md
-a---l 15-10-2024 06:58 PM 173 hello_chai.py

PS C:\Users\harih\OneDrive\Desktop\chai aur python\01-basics> python
Python 3.12.1 (tags/v3.12.1:2305ca5, Dec 7 2023, 22:03:25) [MSC v.1937 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.

> > > print("harry with python")
> > > harry with python
> > > 2*8
> > > 16
> > > 255*410
> > > 104550
> > > 10245554*8618
> > > 88296184372
> > > hiii*5
> > > Traceback (most recent call last):
> > > File "<stdin>", line 1, in <module>
> > > NameError: name 'hiii' is not defined
> > > "hai"\*5
> > > 'haihaihaihaihai'
> > > score = 90
> > > print(score)
> > > 90
> > > score
> > > 90
> > > import os
> > > os.getcwd()
> > > 'C:\\Users\\harih\\OneDrive\\Desktop\\chai aur python\\01-basics'
> > > for n in "harry":
> > > ... print n
> > > File "<stdin>", line 2

    print n
    ^

IndentationError: expected an indented block after 'for' statement on line 1

> > > print (n)
> > > Traceback (most recent call last):
> > > File "<stdin>", line 1, in <module>
> > > NameError: name 'n' is not defined
> > > for n in "harry":
> > > ... print (n)
> > > ...
> > > h
> > > a
> > > r
> > > r
> > > y
> > > import sys
> > > sys.platform
> > > 'win32'
> > > import hello_chai
> > > welcome to chai aur code
> > > irani chai
> > > hell0_chai.chai("masala chai")
> > > Traceback (most recent call last):
> > > File "<stdin>", line 1, in <module>
> > > NameError: name 'hell0_chai' is not defined. Did you mean: 'hello_chai'?
> > > hello_chai.chai("masala chai")
> > > masala chai

> > > hello_chai.chai_one
> > > AttributeError: module 'hello_chai' has no attribute 'chai_one'
> > > from importlib import reload
> > > reload(hello_chai)
> > > welcome to chai aur code
> > > irani chai
> > > <module 'hello_chai' from '/Users/apple/Desktop/Hindi/ CHAI AUR PYTHON/01-basics/hello_chai.py'>
> > > hello_chai.chai_one  
> > > 'chocolate chai'
> > > hello_chai.chai_two
> > > 'ginger chai'
