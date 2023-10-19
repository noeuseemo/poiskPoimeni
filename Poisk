s=open('students.txt','r',encoding='utf-8')

students=[]
for student in s:
        n=student.split(';')
        id=int(n[0])
        surname=n[1]
        name=n[2]
        otchestvo=n[3]
        var=int(n[4])
        group=int(n[5])
        students.append({'id':id,'surname':surname,'name':name,'otchestvo':otchestvo, 'variant':var, 'group':group })
    
s.close()

name=input('Введите имя:')
for student in students:
    if student['name'] == name:
        print(student)
