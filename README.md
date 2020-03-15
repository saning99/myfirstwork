class data:
    def __init__(self,name,surname,dob):
        self.NAME=name 
        self.SURNAME=surname
        self.DOB=dob
        
worker=data(str(input("Please input name: ")),str(input("Please input surname: ")),int(input("Please input date of birth: ")) )


print(worker.NAME, worker.SURNAME)
