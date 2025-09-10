# Exp.No: 5E  Multiple Inheritance
# AIM
To write a Python program using multiple inheritance to get a student’s name, attendance, and ID (grade), and determine if the student is eligible for placement based on their grade.

# ALGORITHM
1. Start the program.
2. Define class A: In the constructor init(), accept input for: n: Student's name a: Student's attendance i: Student's ID (grade) Define class B inheriting from A: Define disp1() to print the name and attendance.
3. Define class C inheriting from A: Define disp2() to check if grade (i) is greater than 90: If yes, print “Eligible for Placement”.
4. Else, print “Not Eligible for Placement”.
5. Define class D that inherits from both B and C (multiple inheritance).
6. Create an object o of class D. Call disp1() to display name and attendance. Call disp2() to check placement eligibility.
7. End the program.
# Program
212223060113-Karnatam Bindu
```
class student:
    def __init__(self,name,id,mark):
        self.name=name
        self.id=id
        self.mark=mark
    def veiw(self):
        print(self.name)
        print(self.id)

id=input()
name=input()
mark=int(input())
s=student(id,name,mark)
s.veiw ()
if mark>=75:
    print("Eligible for Exam")
else:
    print("Not Eligible for Exam")
```
# OUTPUT
<img width="1177" height="343" alt="image" src="https://github.com/user-attachments/assets/2e7f3adf-704c-47dd-97a2-658bf2c63591" />

# RESULT
Thus the python program was initiated and executed successfully.
