# Exp.No:5D Multi-level Inheritance
# AIM
To write a Python program that collects a person's name, age, and salary, and displays them using multilevel inheritance in object-oriented programming.

# ALGORITHM
1. Start the program.
2. Define class a (base class): In the constructor init(), get input for: x → Name (string) a → Age (integer) b → Salary (integer) Define class b inheriting from a: Define dis1() to return name.
3. Define class c inheriting from a: Define dis2() to return age.
4. Define class d inheriting from a: Define dis3() to return salary.
5. Define class e inheriting from b, c, and d: Use pass since it inherits everything needed. Create an object y of class e. Print the outputs from dis1(), dis2(), and dis3().
6. End the program.

# PROGRAM
Reg-212223060113 Name-Karnatam Bindu
```
class a:
def init(self):
self.x=input()
self.a=int(input())
self.b=int(input())
class b(a):
def dis1(self):
return self.x
class c(a):
def dis2(self):
return self.a
class d(a):
def dis3(self):
return self.b
class e(b,c,d):
pass
y=e()
print(y.dis1() ,y.dis2() ,y.dis3())
```
# OUTPUT
<img width="947" height="292" alt="image" src="https://github.com/user-attachments/assets/c63b86c4-aad2-4c4e-878f-ebcd74423138" />

# RESULT 
Thus the python program was initiated and implemented successfully.
