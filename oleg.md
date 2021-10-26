m= ['qwe','rty','uiop',123]
for i in m:
        print(i)





secret = ['secret','апщуыьпщз','sdfgh',2345]
pass1 = '1234'

while True:
    a = input('пароль ')
    if a == pass1:
        a= input('введите номер ')
        print(secret[int(a)])
        b = input('поменяйте пароль ')
        b=input()
        a=input()
        if b == '1':
             pass1 = input()
        elif b == '2':
            c = input('введите номер')
            secret.append(c)
        elif d == '3':
            d = input('Введите номер')
            secret.clear("remove")
    else:
        print('Повторите')
