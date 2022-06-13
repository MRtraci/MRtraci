- 👋 Hi, I’m @MRtraci
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
MRtraci/MRtraci is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def append():
  cars = ["bmw","forza","lada"]
  print(cars)
  print("--------------------*---------------")
  adding = input("what do you want to add in list?:")
  cars.append(adding)
  print("---------------*--------------")
  print(cars)
  ret()


def removing():
  print("**********************")
  print("removing function")
  cars = ["bmw","forza","lada"]
  print(cars)
  removing = input("what do you want to remove?:")
  cars.remove(removing)
  print("----------------*--------------")
  print(cars)
  ret()


def functions():
  appendi = ["add","Add"]
  remove = ["Remove","remove"]
  lengthes = ["length","len"]
  print("select your operation")
  print("--------------*-----------------")
  print("you need add or remove or see the lenght:?")
  print("-----------------*-----------------")
  checkpoint = input("add or remove or length?:")
  if checkpoint in appendi:
    append()
  elif checkpoint in remove:
    removing()
  elif checkpoint in lengthes:
    len()
  else:
    print("wrong operation")
#es funqcia sadac add an removia
print("welcome to adding or removing operation")
print("------------------*-------------------")
print("you need to start your operation?:")
print("-----------------------*------------------")


def ret():
  returnebi = ["Retry","retry","no","No"]
  declinebi = ["Cancel","cancel"]
  print("-----------------------*--------------")
  print("do you want to repeat the program?:")
  print("-------------------*--------------------")
  n9 = input("retry or cancel:")
  if n9 in returnebi:
    functions()
  elif n9 in declinebi:
    exit()
  else:
    print("wrong operation")

def len():
  cars = ["bmw","forza","lada"]
  accept = ["yes","Yes"]
  declinebii = ["no","No"]
  print("------------*--------------")
  print("do you want to know the length of your lists?")
  print("-----------------*--------------")
  n10 = input("yes or no:")
  if n10 in accept:
    len(cars)
  elif n10 in declinebii:
    ret()
  else:
    exit()
  

def close():
  print("you closed the aplication")
  exit()
#es daxurvaa
start = input("yes or no:")
if start == "yes" and "Yes":
  functions()
else:
  close()


