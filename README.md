# school
import math
ass = 500
kok = int(input('сколько будет задач?'))
while ass > kok:
    print('кв или sin?')
    калькулятор = input()
    if калькулятор == ('кв'):
                    a = float(input("Введите A:\n"))
                    b = float(input("Введите B:\n"))
                    c = float(input("Введите C:\n"))
                    y = (b**2)
                    v = (4*a)
                    n = (v * c)
                    ei = (y - n)
                    x1 = -abs(b) - math.sqrt(ei) 
                    thefirstx = (x1 / (2 * a)) 
                    print(f' первый корень = {thefirstx}' )
                    
                    x2 = -abs(b) + math.sqrt(ei) 
                    thesecondtx = (x2 / (2 * a)) 
                    print(f' второй корень = {thesecondtx}' )
                    print(y, v, n, ei, x1)
    import math
    if калькулятор == ('sin'):
        angle_In_Degrees = int(input('градус угла?'))
        angle_In_Radians = math.radians(angle_In_Degrees)
        a = (math.sin(angle_In_Radians))
        print(f' sin угла будет:{round(a, 3)}')

