# Serie para determinar los números consecutivos hasta 10.
s = "Serie: "
for i in range(1, 11):
    s = s +str(i) + ","

s = s.rstrip(",") 
print(s)

# Serie para determinar los números elevados al cuadrado más 1.
s = "Serie: "
for i in range(1, 11): 
    s = (s) + str(i*i) + ","

s = s.rstrip(",") 
print(s)

# Serie para determinar los números consecutivos
n = int(input("Digite N de elementos de la serie: "))

s = "serie :"

for i in range(1,n+1): 
    if i<n: 
        s = s + str(i) + "," 
    else: s = s + str(i)

s = s.rstrip(",") 
print(s)



s = "serie: "

for i in range(1, 12): 
    s = s + str(2**i) + ","

s = s.rstrip(",") 
print(s)



s = "Serie: "

for i in range(1, 11): 
    s = s + "1/" + str(i) + ","

s = s.rstrip(",") 
print(s)




s = "Serie: "

for i in range(1, 11): 
    s = s + "1/" + str(i**2+1) + "," 

s = s.rstrip(",") 
print(s)



s = "Serie: "

for i in range(1, 11): 
    s = s + str(i**2+i) + ","

s = s.rstrip(",") 
print(s)




s = "Serie: "

for i in range(1, 11): 
    s = s + str(i*5-2) + ","

s = s.rstrip(",") 
print(s)



# Serie para determinar si un número es primo.

n = int(input("Digite la cantidad de números a evaluar: "))
w = 0
for i in range(2, n): 
    d = (n%i) 
    if d == 0: 
        w = 1      
      
if w == 0:
    print("Es primo")
else:
    print("No primo")

# Serie para determinar los primeros 100 números de una lista.
n = int(input("Digite la cantidad de números a evaluar: "))

if n>0:
    for i in range(2, n):
        coef = 2
        primo = True
        while coef and primo < i:
            if i % coef == 0:
                primo = False
            else:
                coef += 1
    
        if primo:
            print(i)
            print("\nLos números primos son los siguientes:")
