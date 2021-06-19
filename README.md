# Format-command-in-Python
name=input("Enter Name: ")
Employee_ID=input("Enter Employee ID: ")
Commission_rate=input("Enter Commission Rate: ")
Shift=input("Enter your Shift Morning/Evening: ")
txt="Employee name is {} with ID {} has commission rate {} and work in {} shift"
print(txt.format(name,Employee_ID,Commission_rate,Shift))
