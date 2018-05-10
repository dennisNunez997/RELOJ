# RELOJ
import time

t = time.localtime()

for hour in range(0, 24):  # horas
    time.sleep(24)
    for min in range(0,60): # minutos
        time.sleep(1)
        # print(i)
        # os.system("clear")
        for i in range(0,60): # segundos
            print(str(hour)+':'+str(min)+':'+str(i))
            time.sleep(1)


    
        