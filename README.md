# Modules-Classes-and-Objects
class Student:
    def __init__(self, name, marks):
        self.name = name
        self.marks = marks

    def display(self):
        print(self.name, self.marks)

s1 = Student("Ravi", 85)
s2 = Student("Anita", 92)

s1.display()
s2.display()
output
Ravi 85
Anita 92
