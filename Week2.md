# Chu PY week 2  
  
## Calendar of 2026

import calendar  
year = 2026  
print(calendar.calendar(2026))  
  
<img width="572" height="653" alt="image" src="https://github.com/user-attachments/assets/2d6abc52-cc45-435e-a9ba-a9e170302391" />  

## System version check
import sys  
print(f"python version :{sys.version.split()[0]}")  
  
<img width="360" height="68" alt="image" src="https://github.com/user-attachments/assets/9de3da86-3483-4cc5-96f1-0ad6d2b8f274" />  
<img width="407" height="71" alt="image" src="https://github.com/user-attachments/assets/1e84b78d-6b98-4fe2-b88d-a3e7c41f255d" />  
  
## Python Startup

### P01-01 Hello  
print("Hello, my name is Duncan,a student of PYTHON 2026.")  

<img width="524" height="66" alt="image" src="https://github.com/user-attachments/assets/6dbd9562-0c70-4114-8bfd-6c0285a7d599" />  

### P01-02 My Name  
name = "Duncan"  
print("My name is "+name)  
### P01-03 Self Intro  
name = "Duncan Lin"  
Str1= "it's nice to meet ya!"  
print("My name is "+ name +","+Str1)  

<img width="667" height="443" alt="image" src="https://github.com/user-attachments/assets/00542da7-2962-4877-a64c-cafeece7ae3c" />  

### P01-04 Basic Math
print(10+5)  
print(10-5)  
print(10*5)  
print(10/5)  
print(10**5)  
print(10//5)  
<img width="252" height="331" alt="image" src="https://github.com/user-attachments/assets/4ed84ddb-8b6e-41fa-a282-635253845771" />

### P01-05 Multi Print  
a,b,c=(1,2,3)  
print(a,b,c)  
<img width="215" height="136" alt="image" src="https://github.com/user-attachments/assets/68b5782c-bdc5-4abb-b488-20b512420625" />

### P01-06 Separator 
print("2026","03","02",sep="-")  
print("\n")  
<img width="363" height="100" alt="image" src="https://github.com/user-attachments/assets/9362312e-b2a3-412f-aba9-b7aff9b60a09" />

### P01-07 End parameter
** add space instead of entering next line while separating 2 lines of output **  
print("2026","03","02",sep="-",end=" ")  
print("Hello")  
<img width="488" height="123" alt="image" src="https://github.com/user-attachments/assets/8cfc78e1-acb1-49b2-83bf-d4340fe182a7" />

### P01-08 Swap  
Expect a=5,b=3  
**Pseudoswap**  
a=b  
b=a  
  
**Real Swap**  
temp=a  
a=b  
b=temp  
#### code:
a,b=(5,3)  
a=b  
b=a  
print(a,b)  
a,b=(5,3)  
temp=a  
a=b  
b=temp  
print(a,b)  
<img width="234" height="316" alt="image" src="https://github.com/user-attachments/assets/64af4ac2-8d35-49a1-ba51-8cf1d3829c0e" />

### P01-09 Python Swap  
a,b=(5,3)  
a,b=b,a  
print(a,b)  
<img width="188" height="148" alt="image" src="https://github.com/user-attachments/assets/46a1402a-c9a2-410f-9cf8-a0f566c4d7cb" />  

## Practice
print("2026","03","02",sep="-")  ## Separate date with sep- ##  
print("\n")  ## next line ##
  
a=int(5)  ## the initialization of int is not a must ##  
b=int(10)  
print("a =",a,"b =",b)  
print(10+5,10+a,b+a,sep="\n")  ## add ##  
print("\n")  
  
print(10-5,10-a,b-a,sep="\n")   ## subtract ##  
print("\n")  
  
print(10 * 5,10 * a,b * a,sep="\n")  ## multiply ##  
print("\n")  
  
print(10/5,10/a,b/a,sep="\n")  ## divide ##  
print("\n")  
  
print(10 ** 5,10 ** a,b ** a,sep="\n")  ## square ##
print("\n")  
  
temp=a  ## swap ##  
a=b  
b=temp  
  
print("a =",a,"b =",b)  ## print values after swap ##
  
print(a ** b)  
  

<img width="279" height="636" alt="image" src="https://github.com/user-attachments/assets/da0de407-90fa-47c9-9773-493a2605f831" />  
<img width="206" height="549" alt="image" src="https://github.com/user-attachments/assets/f234fc36-05d8-4c0c-a5ff-69d0bde409ca" />  

## Simplified Version  
a,b=(5,10)  
print(f"a = {a},b = {b}\n")  
print(f"{10+5}\n{10+a}\n{b+a}\n")  
print(f"{10-5}\n{10-a}\n{b-a}\n")  
print(f"{10*5}\n{10*a}\n{b*a}\n")  
print(f"{10/5}\n{10/a}\n{b/a}\n")  
print(f"{10 ** 5}\n{10 ** a}\n{b ** a}\n")  
a,b=b,a  
print(f"a = {a},b = {b}")  
print(f"{a**b}")  
<img width="474" height="296" alt="image" src="https://github.com/user-attachments/assets/30c8b407-77a3-43a4-a10b-ac0c65723b91" />  
<img width="182" height="574" alt="image" src="https://github.com/user-attachments/assets/076da32d-0376-4ea9-b6cc-21446c527ef0" />

