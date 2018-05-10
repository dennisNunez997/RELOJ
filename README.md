# RELOJ
import time
t = time.localtime()
hour= t[3]
min = t[4]
sec = t[5]
for hour in range(hour,24):
    time.sleep(1)
    for min in range(min,60):
        time.sleep(1)
        for k in range(sec,60):
            time.sleep(0)
            print(str(hour) + ":" + str(min) + ":" + str(k))
            time.sleep(1)


    
        