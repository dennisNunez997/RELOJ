# RELOJ
Crear un reloj
import time
t = time.localtime()

for x in range (0,60):
    time.sleep(1)
    for y in range (0,60):
        time.sleep(1)
        for z in range (0,60):
            print(str(z)+":"+str(y)+":"+str(x))
            time.sleep(1)

    
        