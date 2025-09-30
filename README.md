# calculadora de propinas 

costo = float(input("Ingrese el costo de la cuenta: "))
propina = float(input("Ingrese el porcentaje de propina (%):"))
total = costo + (costo * propina / 100)
print(f"Costo: {costo:.2f}")
print(f"Propina: {propina}% = ${costo * propina / 100:.2f}")
print(f"Total: {total:.2f}")


#verificador de edad para votar

edad = int(input("Ingrese su edad: "))
if edad >= 18:
    print("Tiene edad para votar")
else:
    print("No tiene edad para votar")


# suma de numeros pares 


n = int(input("Ingrese un numero: "))
suma = 0
for i in range(1, n + 1):
    if i % 2 == 0:
        suma += i
print(f"La suma de los numeros pares desde 1 hasta {n} es: {suma}")


# adivina el numero secreto


numero_secreto = 510
while True:
    intento = int(input("Ingrese un numero: "))
    if intento < numero_secreto:
        print("Demasiado bajo")
    elif intento > numero_secreto:
        print("Demasiado alto")
    else:
        print("¡Ganaste! El numero secreto era", numero_secreto)
        break


# contador de vocales


texto = input("Ingrese un texto: ")
vocales = 0
for letra in texto:
    if letra.lower() in "aeiou":
        vocales += 1
print(f"El texto tiene {vocales} vocales")



aqui nada mas es los py
