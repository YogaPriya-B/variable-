# variable- 
class Students: fee=20000 no_stu=0 def init(self,name,rollno,dob): self.name=name self.rollno=rollno self.dob=dob Students.no_stu=Students.no_stu + 1
stu1=Students("Yogapriya",142,2003) stu2=Students("Sanjay",153,2006)
print(stu1.fee) print(stu1.dict) print(stu1.fee) print(stu2.fee) print(Students.no_stu)
