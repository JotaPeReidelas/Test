import time
x = 0
y = 0
while 0 == 0:
    print(y," minutos, ",x," segundos")
    x += 1
    time.sleep(1)
    if x > 59:
        y += 1
        x = 0

#esse é codigo de um contador simples e funcional. ele conta os segundos e minutos.
