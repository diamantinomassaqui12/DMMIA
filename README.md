n1=floaut(input("digite o número:))
n2=floaut(input("o outro número:))

print("soma(+)")
print("multiplicação(*)")
print("subtração(-)")
print("divisão(/)")
print("reto(%))
op=input("escolha um dos caracteres em frente das palavras :")

if op =="+":
   soma =n1+n2
   print(f"{n1} + {n2}={soma}")

if op =="*":
   mult=n1*n2
   print(f"{n1} x {n2}={mult}")

if op =="-":
    sub=n1-n2
    print(f"{n1} / {n2}={sub}")

if op =="%":
    rest=n1%n2
    print (f"{n1} % {n2}={rest}")


