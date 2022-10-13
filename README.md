# Ejercicios_series
s = "serie: "

for i in range(1, 11):
    s = (s) + str(i*i) + ","
    

print(s)
----
n = int(input("Digite N de elementos de la serie: "))

s = "serie :"

for i in range(1,n+1):
    if i<n:
        s = s + str(i) + ","
    else:
        s = s + str(i)

print(s)
----
s = "serie: "

for i in range(1, 12):
    s = s + str(2**i) + ","

print(s)
---

s = "Serie: "

for i in range(1, 11):
    s = s + "1/" + str(i) + "," 

print(s)
---
s = "Serie: "

for i in range(1, 11):
    s = s + "1/" + str(i**2+1) + "," 
s = s.rstrip(",")
print(s)
--
s = "Serie: "

for i in range(1, 11):
    s = s + str(i**2+i) + "," 
    

s = s.rstrip(",")
print(s)

--
s = "Serie: "

for i in range(1, 11):
    s = s + str(i*5-2) + "," 
    
s = s.rstrip(",")
print(s)


serie: primeros 100 numeros primos.
