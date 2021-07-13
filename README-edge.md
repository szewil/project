# project
print("welcome to IS and CS community in cmu  please enter your name,major,andrewId")
cs_students=[]
is_students=[]
group=[]
for student in range (2):
 studentname=input("full Name")
 studentmajor=input("Major")
 studentandrewId=input("andrew Id")
 if studentmajor=="CS" :
   cs_students.append(studentname)
   print("the metting is in the first hall")
 elif studentmajor=="IS":
    is_students.append(studentname)
    print("the metting is in the second hall")
 else: 
     print(" you are not a CS or IS student so please recheck the link sent to your email")
print("The  registered students in Computer Science are")
print(cs_students)
file = open("alumini.txt","r")
print(file.name)
for line in lines
print(line)
